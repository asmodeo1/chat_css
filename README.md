# chat_css
En este ejercicio crearemos una página web usando CSS emulando un sencillo chat.

Algunas consideraciones son:
- Para el título, recordad que se puede poner más de una sombra a un texto, separándolas por comas
- Para crear las dos columnas en cada mensaje, la del usuario y la del texto en sí, podríamos usar:
  -  la propiedad display a float en las columnas, como ya hemos estudiado y visto los problemas que conlleva (usar clearfix para solucionarlo)
  -  usar display a inline-block en las columnas, aunque tendremos el problema de conseguir que ambas columnas tengan la misma altura
  -  usar Flexbox o Grid que aún no hemos estudiado
  -  usar display a table en el contenedor principal de los mensajes y display a table-cell en las columnas. En este ejercicio vamos a usar esto. Este modo dará un problema en el borde redondeado, sobresaliendo una zona rectangular. La solución es usar overflow: hidden en el contenedor de los mensajes
 

En el fichero resultado Chat.pdf tenemos como debe quedar, teniendo en cuenta que la sombra amarilla tan exagerada es problema de la creación de documento PDF; en el ejercicio debe ser una sombra menos llamativa.

Algunas propiedades a usar:
- color: color del texto
- background-color: color del fondo
- background-image: imagen de fondo
- background-position: posición de la imagen de fondo
- background-size: tamaño de la imagen de fondo
- background-repeat: si repetir o no la imagen
- text-shadow: para poner una sombra a un texto
- box-shadow: para poner una sombra a un elemento
- border, border-top, border-bottom, border-left y border-right: para poner borde a un elemento
- border-radius: para poner bordes redondeados a un elemento
- margin, margin-top, margin-bottom, margin-left y margin-right: para los márgenes externos de un elemento
- padding, padding-top, padding-bottom, padding-left y padding-right: para los márgenes internos de un elemento
- font-size: para el tamaño de la letra
- font-family: para el tipo de letra (en este ejercicio se usa NeutronsDemoRegular para el título, Segoe UI para el texto del mensaje y Gill Sans para la información del usuario
- font-weight: para el peso de la letra
- text-align: alineación de un elemento en línea
- text-decoration: para la decoración de un texto (subrayado, tachado, ....)
- vertical-align: alineación vertical de un elemento
- width: ancho de un elemento

