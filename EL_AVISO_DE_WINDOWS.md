# Por qué Windows avisa al instalar KanriDO

Cuando abras el instalador, es probable que Windows muestre una ventana azul que dice «Windows ha
protegido tu PC» y que no deja pulsar «Ejecutar» a la primera.

**Por qué sale.** Windows lleva la cuenta de cuántas veces se ha descargado e instalado cada programa
sin incidencias. Un programa recién publicado no tiene todavía esa reputación, así que el sistema
avisa por precaución. No significa que el archivo tenga nada malo: significa que Windows aún no lo
conoce. El aviso desaparece solo con el tiempo, según se vaya instalando.

**Este aviso merece atención, no costumbre.** Antes de continuar con cualquier programa que lo
muestre, conviene comprobar que el archivo es el que dice ser. Aquí abajo está cómo hacerlo con este.

## Cómo continuar

1. En la ventana azul, pulsa **Más información**.
2. Aparece el nombre del archivo y el botón **Ejecutar de todas formas**.
3. Comprueba que el nombre del archivo es el que has descargado de la página de publicaciones.
4. Pulsa **Ejecutar de todas formas**.

## Cómo comprobar que el archivo es el publicado

Cada instalador que se publica aquí lleva al lado una huella: una cadena de letras y números que se
calcula a partir del contenido del archivo. Si cambia un solo byte, la huella cambia entera.
Comparar la tuya con la publicada confirma que has descargado exactamente el archivo que se publicó.

Para calcularla, abre PowerShell en la carpeta de descargas y escribe:

```
Get-FileHash -Algorithm SHA256 .\KanriDO_1.0.0_x64-setup.exe
```

Cambia el número de versión por el del archivo que hayas descargado. Compara el resultado con la
huella que aparece junto a la descarga, en la publicación de esa versión. Si coinciden, el archivo es
el correcto. Si no coinciden, no lo instales y escribe a kanrido.contact@gmail.com.
