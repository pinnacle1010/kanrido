# Política de privacidad de KanriDO

Última actualización: 14 de octubre de 2026.

## 1. Responsable del tratamiento

- **Responsable**: César Calabuig Llamas.
- **Contacto**: kanrido.contact@gmail.com.

Esta política cubre **la página de descargas de KanriDO** (github.com/pinnacle1010/kanrido) y el
contacto por correo. La aplicación se trata aparte, en el apartado 2, porque su situación es
distinta.

## 2. Qué envía la aplicación

KanriDO es una aplicación de **escritorio local**. Los datos que el usuario importa o introduce
—proyectos, facturación, horas, gastos, indicadores— se guardan **cifrados en su propio equipo** y no salen de él.

No hay cuenta, ni registro, ni comprobación de licencia, ni informes de uso, ni informes automáticos
de error. Funciona sin conexión a internet.

En internet solo hace dos cosas:

- **Un aviso único tras instalarse.** La primera vez que arranca una instalación nueva, envía una
  petición sin ningún contenido a un servicio de César Calabuig Llamas alojado en Cloudflare. El
  servicio deduce de la dirección IP el país desde el que llega, anota ese país y el día, y no
  conserva la IP. Sirve para saber cuántas instalaciones hay, en qué países y a qué ritmo. Las
  actualizaciones no lo vuelven a enviar.
- **Comprobar, al arrancar, si hay una versión nueva**: pide a GitHub, donde se publican las
  versiones, el archivo que dice cuál es la última. Esa petición no lleva ningún dato de negocio ni
  ningún identificador del usuario; GitHub ve la dirección IP desde la que se hace, como en
  cualquier visita, y la trata según su propia política. La versión nueva solo se descarga si el
  usuario lo pide.

En consecuencia, respecto de los datos que el usuario trata con la aplicación, César Calabuig Llamas
**no es responsable ni encargado del tratamiento**: no los recibe, no los aloja y no puede acceder a
ellos. El responsable de esos datos es el propio usuario, y ejerce sus derechos sobre ellos
directamente desde la aplicación, sin intervención de nadie.

Las copias de seguridad se guardan en la carpeta que elige el usuario, en su equipo o en el servicio
de almacenamiento que él tenga configurado. César Calabuig Llamas no interviene en ello.

## 3. Qué trata César Calabuig Llamas

No hay web propia: la página de descargas es un repositorio de GitHub (apartado 4). Por parte de
César Calabuig Llamas solo se trata esto, y ningún otro dato:

| Dato | Finalidad | Base jurídica (RGPD art. 6) |
|---|---|---|
| Dirección IP del aviso de instalación, solo para deducir el país; se guardan el país y el día, no la IP | Contar las instalaciones por país y por día | Interés legítimo |
| Dirección de correo y contenido del mensaje, si el usuario escribe | Atender la consulta o el aviso de fallo | Interés legítimo / consentimiento |

No se usa ninguna herramienta de analítica ni se instalan cookies. Si algún día hay una web propia,
esta política dirá aquí qué datos trata antes de que empiece a tratarlos.

## 4. Descargas

La descarga se aloja en GitHub, que registra las descargas conforme a su propia política de
privacidad, sobre la que César Calabuig Llamas no tiene control:
https://docs.github.com/es/site-policy/privacy-policies/github-general-privacy-statement. La
comprobación de versiones nuevas del apartado 2 llega también a GitHub.

## 5. Destinatarios

No se venden ni se ceden datos a terceros con fines comerciales.

Intervienen GitHub, que aloja la descarga y trata los metadatos de cada petición según su propia
política; Cloudflare, que aloja el servicio que cuenta las instalaciones y recibe la dirección IP del
aviso del apartado 2, y Google (Gmail), que sirve el correo de contacto.

## 6. Transferencias internacionales

Si algún proveedor trata datos fuera del Espacio Económico Europeo, la transferencia se ampara en
las **Cláusulas Contractuales Tipo** de la Comisión Europea o en otra garantía adecuada (RGPD, cap.
V).

## 7. Conservación

Los mensajes de contacto se conservan mientras dure la consulta y, después, durante los plazos
legales aplicables.

El registro de instalaciones, con su país y su día, se conserva mientras se publique la aplicación.
No contiene datos personales.

## 8. Derechos

El usuario puede ejercer los derechos de **acceso, rectificación, supresión, oposición, limitación y
portabilidad** escribiendo a kanrido.contact@gmail.com. También puede reclamar ante la **Agencia
Española de Protección de Datos** (www.aepd.es).

> Sobre los datos de negocio que el usuario tiene en la aplicación, estos derechos no se ejercen
> ante César Calabuig Llamas, que no los tiene: se ejercen desde la propia aplicación, que permite
> consultarlos, exportarlos y borrarlos.

## 9. Seguridad

En la aplicación: la base de datos local va cifrada con **SQLCipher (AES-256)**, la clave vive en el
almacén seguro del sistema operativo y, opcionalmente, en un llavero protegido con la contraseña del
usuario que acompaña a las copias de seguridad.

La página de descargas, el aviso de instalación y la comprobación de versiones nuevas van por
**HTTPS**.

## 10. Cambios en esta política

La versión vigente se publica en
https://github.com/pinnacle1010/kanrido/blob/main/POLITICA_DE_PRIVACIDAD.md, con la fecha de la
última actualización.

---
