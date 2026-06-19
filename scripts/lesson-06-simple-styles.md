# Lección 6: Estilo simple con CSS

**Duración recomendada:** 7-8 minutos

## Objetivo

Que el estudiante aplique estilos simples comprendiendo el modelo de caja (margin/padding), centre contenido y cree un botón interactivo.

## Guion base

¡Hola y bienvenidos a la lección 6! En nuestra lección anterior aprendimos cómo funciona CSS y cómo podemos cambiar colores básicos. Pero hoy vamos a dar un paso mucho más grande. En esta lección vamos a mejorar el diseño de una página usando estilos simples, para que se vea como una tarjeta de perfil real, moderna y atractiva, tal como las que ven en sus redes sociales favoritas.

Vamos a practicar creando una caja o tarjeta. Esta tarjeta tendrá un fondo bonito, bordes, espacio para respirar y estará perfectamente centrada en la pantalla.

Antes de empezar a escribir código, tenemos que entender un concepto muy importante. En el desarrollo web, absolutamente todo es una caja. Imaginen que cada elemento de su página es una caja invisible. Y para acomodar y separar estas cajas, usamos dos cosas llamadas padding y margin.

El padding es el espacio interno, es como el relleno suavecito de una almohada que protege lo que hay adentro. El margin es el espacio externo, es como la distancia que hay entre tu casa y la casa de tu vecino. Entender esto hará que diseñar sea súper fácil.

Primero escribimos este HTML: creamos un div con la clase tarjeta. Adentro ponemos un título h1 que diga Mi tarjeta, y un párrafo que diga Estoy practicando estilos con CSS. Cerramos el div.

Ahora vamos a escribir CSS paso a paso. Primero cambiaremos el estilo general de toda nuestra página web usando el body:

escribimos el selector body, abrimos llaves. Ponemos font-family, dos puntos, Arial, coma, sans-serif. Luego background-color, dos puntos, y el código e 8 f 0 f e. Por último, text-align, dos puntos, center. Cerramos llaves.

Explicación de lo que acabamos de hacer: font-family cambia la fuente de letra aburrida por una más limpia. background-color cambia el color de fondo a un azul muy clarito. text-align center hace que todo nuestro texto se vaya al medio de la pantalla.

Ahora le daremos estilo a la tarjeta para que parezca de verdad:

escribimos punto tarjeta, abrimos llaves. Ponemos background-color, dos puntos, white. border, dos puntos, 2 píxeles, solid, y el código 3 3 3. padding, dos puntos, 20 píxeles. margin, dos puntos, 40 píxeles, auto. Y width, dos puntos, 50 por ciento. Cerramos llaves.

Vamos a explicar esta magia paso a paso: background-color white le coloca un fondo blanco limpio a nuestra caja. border le agrega una línea alrededor para que se distinga del fondo. padding crea el espacio interno para que el texto no choque con los bordes de la caja. margin crea el espacio externo. Al escribir 40 píxeles y luego auto, los 40 píxeles dan el espacio arriba y abajo. Y la palabra mágica auto empuja la tarjeta a los lados por igual para que quede perfectamente centrada en tu pantalla. Finalmente, width hace que la tarjeta ocupe exactamente la mitad del tamaño de la pantalla.

Ahora agregamos bordes redondeados para que no se vea tan cuadrada. En nuestra misma clase tarjeta que ya teníamos, agregamos abajo:

border-radius, dos puntos, 10 píxeles.

Ahora la tarjeta se ve mucho más moderna y amigable.

Recuerda abrir el enlace de CodePen que está en la descripción de este video. Una vez ahí, pausa el video y cambia el color de fondo de la página. Prueba con los colores f c e 4 e c, e 0 f 7 f a, o f f f 9 c 4. Descubre cuál te gusta más.

Continuamos. Nuestra tarjeta se ve bien, pero le falta vida. Vamos a mejorar una imagen. En HTML agregamos una etiqueta img con nuestra foto de perfil.

En CSS escribimos: selector img, abrimos llaves. width, dos puntos, 150 píxeles. border-radius, dos puntos, 50 por ciento. Cerramos llaves.

width cambia el tamaño de la imagen. Y aquí viene un truco genial: border-radius en 50 por ciento hace que cualquier imagen cuadrada se convierta en un círculo perfecto.

Ahora agreguemos un botón usando un simple enlace. En HTML colocamos una etiqueta a con el texto Buscar información.

En CSS: selector a, abrimos llaves. color, dos puntos, white. background-color, dos puntos, y el código 1 9 7 6 d 2. padding, dos puntos, 10 píxeles y 15 píxeles. border-radius, dos puntos, 8 píxeles. text-decoration, dos puntos, none. Cerramos llaves.

Explicación: color cambia el color del texto a blanco. background-color le da un fondo azul intenso al enlace. padding le da ese relleno interno para que parezca un botón real. border-radius le redondea un poco las esquinas. Y text-decoration en none quita esa línea fea de subrayado que traen los enlaces por defecto.

Para que nuestro botón sea increíble, haremos que cambie de color cuando lo tocamos. En CSS escribimos: selector a, dos puntos, hover, abrimos llaves. background-color, dos puntos, y el código 1 5 6 5 c 0. Cerramos llaves.

La palabra hover significa sobrevolar. Con esto, le decimos a la página que cuando el cursor del mouse pase por encima del botón, el fondo cambie a un azul mucho más oscuro. ¡Pruébenlo!

Ahora hablemos de diseño limpio y errores comunes. Cuando estamos empezando a diseñar, es súper recomendable no usar demasiados colores mezclados. Es mejor usar uno o dos colores principales y mantener el diseño ordenado.

También debemos cuidar que el texto siempre se pueda leer bien. Esto se llama contraste. Por ejemplo, si usamos un fondo oscuro, el texto debe ser de color claro. Si usamos un fondo muy claro, el texto debe ser oscuro.

Un consejo extra: si alguna vez escriben un estilo y ven que no funciona en la pantalla, no se asusten. El error más común cuando aprendemos es olvidar cerrar una regla con el punto y coma, o olvidar cerrar las llaves. Siempre revisen su código.

Pausa el video por un minuto, modifica el color del botón y revisa si el texto de adentro se sigue leyendo bien.

Para cerrar esta lección, hagamos un repaso rápido de lo que logramos hoy: Aprendimos a centrar contenido de forma automática. Entendimos la diferencia entre margen interno y externo. Creamos una tarjeta moderna. Convertimos imágenes cuadradas en círculos. Y transformamos un simple enlace de texto en un botón interactivo y profesional. ¡Nos vemos en la siguiente lección!

## Práctica

Abre el enlace de CodePen correspondiente a esta lección, modifica el color de fondo de la página y el color del botón para probar el contraste, y visualiza el resultado en vivo en el navegador.

## Cierre

En esta lección aprendimos conceptos clave sobre el modelo de caja y estilos para construir páginas web. En la siguiente clase continuaremos agregando más elementos para finalizar nuestro proyecto.