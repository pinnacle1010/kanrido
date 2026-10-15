*Read this in English: [README.en.md](README.en.md)*

# KanriDO

Los indicadores de tu negocio, calculados a partir de los archivos que ya tienes.

KanriDO es una aplicación de escritorio para Windows. Importa tus hojas de cálculo en el formato en
que ya las llevas, calcula los indicadores y los muestra en un dashboard. Los datos se quedan
cifrados en tu equipo: no hay que subirlos a ningún sitio ni darse de alta en nada.

**La aplicación es gratuita y todo el mundo recibe la misma versión.** No hay planes, ni prueba
limitada, ni nada que caduque.

## Descargar

La última versión está en la página de [**Releases**](../../releases/latest), con el instalador
adjunto y su huella SHA-256 al lado.

- Windows 10 o Windows 11, de 64 bits.
- Al abrir el instalador, Windows muestra un aviso: está explicado en
  [El aviso de Windows](EL_AVISO_DE_WINDOWS.md), junto con cómo comprobar que el archivo es el
  correcto.
- El instalador pregunta el idioma y muestra las condiciones de uso, que hay que aceptar para
  continuar.

## Para quién es

Está pensada para empresas pequeñas que trabajan por proyectos: despachos técnicos, arquitectura e
ingeniería, consultoras, estudios de diseño y proyectos rurales o forestales. Si llevas la
facturación, las horas y los gastos repartidos entre varias hojas de cálculo, esto sirve para
juntarlos y ver cómo va cada proyecto.

## Qué hace

- **Importar lo que ya tienes.** Excel y CSV, con sus columnas y sus formatos. También puede vigilar
  una carpeta e importar sola lo que aparezca.
- **Calcular los indicadores.** Facturación, horas imputadas, gastos, propuestas y el estado de cada
  proyecto, por periodo y por línea de negocio.
- **Mostrarlos en un dashboard.** Varios dashboards en pestañas, cada uno con los indicadores que
  elijas, y una vista por proyecto.
- **Dejar los datos en tu equipo.** La base va cifrada, con copia de seguridad automática a la
  carpeta que elijas.

**Lo que todavía no está:** la conexión con Google Sheets y con Google Calendar llegará más adelante.
Mientras tanto, una hoja de Google se descarga como Excel o CSV y se importa igual que cualquier otro
archivo.

## Cómo se usa

El [manual](MANUAL.md) explica, con capturas, cómo traer tus datos, cómo leer las cifras, cómo
organizar tus dashboards e indicadores y cómo trabajar con tus proyectos. También está en
[PDF](MANUAL.pdf), para descargarlo o imprimirlo.

## Tus datos

KanriDO no envía datos de negocio, ni informes de uso, ni informes automáticos de error. Todo lo
que importas vive cifrado en tu equipo, y las copias de seguridad van a la carpeta que tú elijas.

En internet solo hace dos cosas. La primera vez que arranca tras instalarse, envía un aviso vacío
que cuenta las instalaciones por país y por día, sin guardar tu dirección IP. Y al arrancar
consulta en esta misma página si hay una versión nueva: si la hay, te avisa, y solo la descarga e
instala si se lo pides.

La contraseña local es la llave: si se pierde a la vez que el equipo, los datos cifrados no se pueden
recuperar. Eso también vale para las copias.

## Avisar de un fallo o proponer una mejora

Escribe a **kanrido.contact@gmail.com**, o abre un tema en la pestaña
[Issues](../../issues) de este repositorio.

Al escribir, indica la versión que aparece en «Acerca de», qué estabas haciendo y qué esperabas ver.
Si el problema es con un archivo concreto, describe cómo son sus columnas. **No hace falta enviar el
archivo ni tus datos**, y conviene no hacerlo: KanriDO no envía tus datos fuera de tu equipo y el correo
tampoco debería.

## Quién está detrás

KanriDO lo desarrolla y publica **César Calabuig Llamas**, a título personal.

- Correo: kanrido.contact@gmail.com
- LinkedIn: https://www.linkedin.com/in/calabuig-cesar/

## Condiciones

- [Condiciones de uso](CONDICIONES_DE_USO.txt)
- [Política de privacidad](POLITICA_DE_PRIVACIDAD.md)

KanriDO es gratuito y se puede usar en la empresa que lo descarga, pero no se puede redistribuir ni
copiar para terceros.
