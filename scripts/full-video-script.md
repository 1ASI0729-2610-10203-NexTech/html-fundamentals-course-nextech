
============================================================
LECCIÓN 1 - ¿QUÉ ES UN SITIO WEB?
RESPONSABLE INTERNO: DAVICHO
DURACIÓN: 7 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante entienda qué es un sitio web, qué tecnologías básicas se usan y por qué HTML y CSS son importantes.

EN PANTALLA:
Título: "Lección 1: ¿Qué es un sitio web?"
Subtítulo: "HTML = contenido | CSS = diseño | JavaScript = interacción"

GUION:

Hola, bienvenidos a este curso básico de desarrollo web. En este curso aprenderemos cómo se crea una página web sencilla usando HTML y CSS. No necesitan tener experiencia previa en programación, porque vamos a empezar desde cero y con ejemplos fáciles.

Primero respondamos una pregunta importante: ¿qué es un sitio web?

Un sitio web es un conjunto de páginas que podemos visitar desde internet usando un navegador. Por ejemplo, cuando entramos a una página de noticias, una tienda online, un blog, una red social o una página de videos, estamos visitando un sitio web.

Para ver un sitio web usamos un navegador. Algunos navegadores conocidos son Google Chrome, Microsoft Edge, Firefox y Safari. El navegador interpreta el código de la página y nos muestra el resultado de forma visual.

Ahora pensemos en ejemplos reales. Cuando entramos a YouTube, vemos videos, botones, títulos, imágenes y comentarios. Cuando entramos a una tienda online, vemos productos, precios, imágenes y enlaces para comprar. Cuando entramos a una página escolar, vemos información del colegio, horarios, cursos y noticias.

Todo eso no aparece por magia. Detrás de cada página hay código. Para crear páginas web se usan principalmente tres tecnologías: HTML, CSS y JavaScript.

HTML sirve para crear la estructura y el contenido de la página. Con HTML podemos colocar títulos, textos, imágenes, listas, enlaces y secciones.

CSS sirve para darle diseño a ese contenido. Con CSS podemos cambiar colores, fuentes, tamaños, bordes, espacios, fondos y la forma en que se acomodan los elementos.

JavaScript sirve para agregar interacción. Por ejemplo, botones que muestran un mensaje, formularios que revisan datos o menús que se abren y se cierran.

En este curso nos vamos a enfocar en HTML y CSS, porque son las bases para empezar en el desarrollo web.

PAUSA VISUAL 1:
Mostrar en pantalla una tabla simple:
HTML = estructura
CSS = diseño
JavaScript = interacción

Continuamos con una comparación sencilla. Imaginemos que una página web es como una casa. HTML sería la estructura de la casa: paredes, puertas, ventanas y habitaciones. CSS sería la pintura, los colores, la decoración y los muebles. JavaScript sería la parte interactiva, como las luces, los interruptores o una puerta automática.

Si solo tenemos HTML, la página puede funcionar, pero se verá muy simple. Si agregamos CSS, la página se verá más agradable y ordenada. Por eso ambos son importantes.

Ahora, para aprender desarrollo web, no necesitamos instalar programas complicados. En este curso usaremos un editor online. Un editor online es una página donde podemos escribir código y ver el resultado al instante desde el navegador.

Algunas opciones son CodePen, JSFiddle o Replit. Para este curso, recomendamos usar CodePen porque es fácil para principiantes. Tiene una zona para HTML, una zona para CSS y una zona donde aparece el resultado.

ACCIÓN EN PANTALLA:
Abrir CodePen.
Mostrar que hay secciones para HTML, CSS y resultado.
No escribir todavía mucho código, solo mostrar la interfaz.

Ahora hagamos una mini práctica para entender la idea. En la zona de HTML escribimos:

<h1>Hola mundo</h1>
<p>Estoy aprendiendo desarrollo web.</p>

Al escribir esto, veremos un título grande y un párrafo en la vista de resultado. Esto nos muestra que HTML sirve para colocar contenido en una página.

PAUSA DE PRÁCTICA 1 MINUTO:
Indicar al estudiante:
"Ahora pausa el video por un minuto, abre CodePen o tu editor online favorito y escribe el mismo ejemplo."

Después de la pausa, continuamos.

Muy bien. Lo importante de esta primera lección es entender que un sitio web está formado por páginas que el navegador puede mostrar. HTML nos ayuda a crear el contenido, CSS nos ayuda a mejorar el diseño y JavaScript nos ayuda a crear interacción.

En la siguiente lección veremos la estructura básica de una página HTML.

RESUMEN EN PANTALLA:
- Un sitio web se abre con un navegador.
- HTML organiza el contenido.
- CSS mejora el diseño.
- Usaremos editores online, sin instalar nada.

============================================================
LECCIÓN 2 - PRIMERA ESTRUCTURA HTML
RESPONSABLE INTERNO: DAVICHO
DURACIÓN: 8 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante conozca la estructura básica de un documento HTML y entienda para qué sirven head, title y body.

EN PANTALLA:
Título: "Lección 2: Estructura HTML básica"

GUION:

En esta lección aprenderemos cómo se organiza una página HTML básica. HTML significa HyperText Markup Language. En español podemos entenderlo como lenguaje de marcado de hipertexto.

Aunque el nombre suena complicado, la idea es sencilla: HTML nos permite decirle al navegador qué contenido queremos mostrar y qué tipo de contenido es.

Por ejemplo, si queremos un título, usamos una etiqueta de título. Si queremos un párrafo, usamos una etiqueta de párrafo. Si queremos una imagen, usamos una etiqueta de imagen.

Ahora veremos una estructura HTML completa. En un archivo HTML tradicional, la estructura se ve así:

<!DOCTYPE html>
<html>
<head>
    <title>Mi primera página</title>
</head>
<body>
    <h1>Hola mundo</h1>
    <p>Esta es mi primera página web.</p>
</body>
</html>

Vamos a explicar cada parte con calma.

La línea <!DOCTYPE html> le indica al navegador que estamos usando una versión moderna de HTML. Es como decirle: "Este documento es una página web actual".

La etiqueta <html> representa todo el documento HTML. Dentro de esta etiqueta estará todo el contenido y la información de la página.

Dentro de <html> encontramos dos partes importantes: <head> y <body>.

La etiqueta <head> no muestra contenido directamente en la página. Sirve para colocar información de la página, por ejemplo el título que aparece en la pestaña del navegador.

La etiqueta <title> define ese título de la pestaña. Si escribimos <title>Mi primera página</title>, en la pestaña del navegador aparecerá ese texto.

La etiqueta <body> es la parte visible. Todo lo que coloquemos dentro de body será lo que el usuario verá en la página: títulos, párrafos, imágenes, listas, enlaces y más.

Ahora veamos estas dos líneas:

<h1>Hola mundo</h1>
<p>Esta es mi primera página web.</p>

La etiqueta <h1> sirve para escribir un título principal. La etiqueta <p> sirve para escribir un párrafo.

ACCIÓN EN PANTALLA:
Mostrar el código completo en una diapositiva o en el editor.
Resaltar con el cursor: doctype, html, head, title, body, h1 y p.

Ahora es importante aclarar algo. En CodePen no siempre necesitamos escribir toda la estructura con <!DOCTYPE html>, <html>, <head> y <body>, porque CodePen ya nos prepara esa parte. En CodePen normalmente escribimos directamente lo que iría dentro del body.

Por eso, en CodePen podemos escribir solo:

<h1>Mi primera página web</h1>
<p>Hola, estoy aprendiendo HTML desde cero.</p>

El resultado será el mismo: veremos un título y un párrafo.

Ahora hagamos una práctica.

PRÁCTICA GUIADA:
En CodePen, en la sección HTML, escribimos:

<h1>Mi primera página web</h1>
<p>Hola, mi nombre es estudiante y estoy aprendiendo a crear páginas web.</p>
<p>Esta página fue creada usando HTML.</p>

Explicación:
El primer elemento es un título principal.
Luego tenemos dos párrafos.
Cada párrafo está separado porque usamos dos etiquetas <p> diferentes.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Cambia el texto del título por el nombre de tu propia página. Por ejemplo: Mi blog, Mi perfil o Mi página de práctica."

Continuamos.

Ahora vamos a hablar de etiquetas de apertura y cierre. Muchas etiquetas HTML tienen una etiqueta de apertura y una etiqueta de cierre.

Por ejemplo:

<p>Este es un párrafo</p>

La primera parte, <p>, abre el párrafo. La segunda parte, </p>, cierra el párrafo. La diferencia es que la etiqueta de cierre tiene una barra inclinada.

Lo mismo ocurre con los títulos:

<h1>Bienvenidos</h1>

Si olvidamos cerrar una etiqueta, el navegador puede confundirse y mostrar el contenido de forma incorrecta. Por eso debemos revisar que nuestras etiquetas estén completas.

Veamos un error común:

<h1>Bienvenidos

Aquí falta cerrar con </h1>. Lo correcto sería:

<h1>Bienvenidos</h1>

ACCIÓN EN PANTALLA:
Mostrar primero el error.
Luego corregirlo.
Decir: "Los errores son normales, lo importante es aprender a revisarlos."

Ahora vamos a agregar un subtítulo. HTML tiene encabezados desde h1 hasta h6. El h1 es el más importante y normalmente se usa para el título principal. El h2 se usa para secciones importantes. El h3 para subsecciones.

Ejemplo:

<h1>Mi página personal</h1>
<h2>Sobre mí</h2>
<p>Me gusta aprender tecnología y crear cosas nuevas.</p>

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Agrega un subtítulo con h2 y escribe un párrafo debajo."

Para cerrar esta lección, recordemos:
HTML organiza la página usando etiquetas.
Una página completa tiene head y body.
El head contiene información de la página.
El body contiene lo que se ve.
En CodePen podemos escribir directamente el contenido del body.

RESUMEN EN PANTALLA:
- <!DOCTYPE html>: indica HTML moderno.
- <html>: contiene toda la página.
- <head>: información de la página.
- <title>: título de la pestaña.
- <body>: contenido visible.
- <h1> y <p>: título y párrafo.

============================================================
LECCIÓN 3 - ETIQUETAS, ELEMENTOS Y ATRIBUTOS
RESPONSABLE INTERNO: SOFÍA
DURACIÓN: 7 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante diferencie etiqueta, elemento y atributo.

EN PANTALLA:
Título: "Lección 3: Etiquetas, elementos y atributos"

GUION:

Ahora que ya conocemos la estructura básica de HTML, vamos a ver tres conceptos muy importantes: etiquetas, elementos y atributos.

Primero, ¿qué es una etiqueta?

Una etiqueta es una palabra especial de HTML que va entre los signos menor que y mayor que. Por ejemplo:

<p>

Esta etiqueta indica el inicio de un párrafo.

La etiqueta de cierre se escribe casi igual, pero con una barra inclinada:

</p>

Entonces, si queremos escribir un párrafo completo, usamos:

<p>Estoy aprendiendo HTML.</p>

Ahora, ¿qué es un elemento?

Un elemento HTML es el conjunto formado por la etiqueta de apertura, el contenido y la etiqueta de cierre.

Por ejemplo:

<p>Estoy aprendiendo HTML.</p>

Todo eso completo es un elemento de párrafo.

Otro ejemplo:

<h1>Mi título principal</h1>

Todo eso completo es un elemento de encabezado.

ACCIÓN EN PANTALLA:
Mostrar una anotación:
Etiqueta de apertura: <p>
Contenido: Estoy aprendiendo HTML.
Etiqueta de cierre: </p>
Elemento completo: <p>Estoy aprendiendo HTML.</p>

Ahora veremos qué son los atributos.

Un atributo es información extra que se agrega dentro de una etiqueta de apertura. Los atributos sirven para configurar o completar la función de una etiqueta.

Por ejemplo, la etiqueta de enlace se escribe así:

<a href="https://www.google.com">Ir a Google</a>

Aquí tenemos un atributo llamado href. El atributo href indica a qué página nos llevará el enlace.

El texto "Ir a Google" es lo que verá el usuario en la página.

Otro ejemplo importante es la imagen:

<img src="https://via.placeholder.com/150" alt="Imagen de ejemplo">

Aquí la etiqueta es img.

El atributo src indica la dirección de la imagen. Es decir, de dónde se obtiene la imagen.

El atributo alt es una descripción de la imagen. Esta descripción es útil cuando la imagen no carga y también ayuda a personas que usan lectores de pantalla.

Algo importante: la etiqueta img no necesita etiqueta de cierre. No escribimos </img>. Solo escribimos la etiqueta con sus atributos.

Ahora vamos a practicar.

En CodePen, escribimos:

<h1>Mi página de práctica</h1>
<p>Estoy aprendiendo etiquetas, elementos y atributos.</p>
<a href="https://www.google.com">Visitar Google</a>

Ahora observamos el resultado. Aparece un título, un párrafo y un enlace. Si hacemos clic en el enlace, nos llevará a Google.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Cambia el texto del enlace. Por ejemplo, en vez de 'Visitar Google', escribe 'Buscar información'."

Continuamos.

Ahora agregaremos una imagen:

<img src="https://via.placeholder.com/150" alt="Imagen de práctica">

Vemos que aparece una imagen de ejemplo. En una página real podríamos usar otra imagen, siempre que tengamos una dirección válida.

Ahora comparemos:
- Las etiquetas dicen qué tipo de contenido usamos.
- Los elementos son la etiqueta completa con contenido.
- Los atributos agregan información adicional.

EJEMPLO EN PANTALLA:
<a href="https://www.google.com">Ir a Google</a>

Etiqueta: <a>
Atributo: href
Valor del atributo: https://www.google.com
Contenido visible: Ir a Google
Elemento completo: toda la línea

Ahora revisemos un error común con atributos.

Incorrecto:
<a href=https://www.google.com>Ir a Google</a>

Mejor:
<a href="https://www.google.com">Ir a Google</a>

Lo recomendable es usar comillas para los valores de los atributos. Así el código queda más claro y correcto.

Para cerrar esta lección, recordemos:
Una etiqueta indica el tipo de contenido.
Un elemento incluye etiqueta de apertura, contenido y etiqueta de cierre.
Un atributo agrega información extra a una etiqueta.

RESUMEN EN PANTALLA:
- Etiqueta: <p>
- Elemento: <p>Texto</p>
- Atributo: href, src, alt
- Los atributos suelen escribirse con comillas.

============================================================
LECCIÓN 4 - ELEMENTOS HTML COMUNES
RESPONSABLE INTERNO: SOFÍA
DURACIÓN: 8 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante use encabezados, párrafos, listas, imágenes y enlaces en una página sencilla.

EN PANTALLA:
Título: "Lección 4: Elementos HTML comunes"

GUION:

En esta lección veremos algunos elementos HTML que se usan con mucha frecuencia al crear páginas web.

Los elementos que veremos son:
Encabezados, párrafos, listas, imágenes y enlaces.

Primero veremos los encabezados.

Los encabezados sirven para crear títulos y subtítulos. HTML tiene encabezados desde h1 hasta h6.

El h1 es el título principal. Normalmente se usa una sola vez en una página.

El h2 se usa para secciones importantes.

El h3 se usa para subsecciones.

Ejemplo:

<h1>Mi blog personal</h1>
<h2>Sobre mí</h2>
<h3>Mis pasatiempos</h3>

ACCIÓN EN PANTALLA:
Escribir el ejemplo en CodePen.
Mostrar cómo se ven los tamaños.

Ahora veremos los párrafos. Los párrafos se crean con la etiqueta p.

Ejemplo:

<p>Hola, esta es mi primera página web. Estoy aprendiendo HTML paso a paso.</p>

Los párrafos sirven para escribir texto normal. Si queremos separar ideas, podemos usar varios párrafos.

Ejemplo:

<p>Me gusta aprender sobre tecnología.</p>
<p>También me gusta crear proyectos pequeños para practicar.</p>

Ahora veremos las listas.

Tenemos listas desordenadas y listas ordenadas.

Una lista desordenada se usa cuando el orden no importa. Se crea con ul y cada elemento se coloca con li.

Ejemplo:

<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

Esto se verá como una lista con viñetas.

Una lista ordenada se usa cuando el orden sí importa. Se crea con ol.

Ejemplo:

<ol>
    <li>Abrir CodePen</li>
    <li>Escribir HTML</li>
    <li>Ver el resultado</li>
</ol>

Esto se verá como una lista numerada.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Crea una lista con tres cosas que te gustan. Puede ser música, deportes, videojuegos, películas o cualquier tema."

Continuamos.

Ahora veremos imágenes.

Para agregar una imagen usamos la etiqueta img:

<img src="https://via.placeholder.com/200" alt="Imagen de ejemplo">

Recordemos que src indica la dirección de la imagen y alt describe la imagen.

El alt es importante porque ayuda a entender qué debería mostrarse si la imagen no carga.

Ahora veremos enlaces.

Los enlaces se crean con la etiqueta a y el atributo href:

<a href="https://www.google.com">Buscar en Google</a>

El atributo href contiene la dirección a la que queremos ir.

Ahora vamos a juntar todo en una mini página llamada "Sobre mí".

En CodePen escribimos:

<h1>Sobre mí</h1>

<p>Hola, soy estudiante y estoy aprendiendo a crear páginas web.</p>

<h2>Mis gustos</h2>

<ul>
    <li>Escuchar música</li>
    <li>Jugar videojuegos</li>
    <li>Aprender tecnología</li>
</ul>

<h2>Mi imagen</h2>

<img src="https://via.placeholder.com/200" alt="Imagen de perfil">

<p>
    Puedes buscar más información aquí:
    <a href="https://www.google.com">Google</a>
</p>

Ahora observamos el resultado. Ya tenemos una pequeña página con título, texto, lista, imagen y enlace.

ACCIÓN EN PANTALLA:
Resaltar cada parte:
- h1: título
- p: párrafo
- ul/li: lista
- img: imagen
- a: enlace

PAUSA DE PRÁCTICA 2 MINUTOS:
Pedir al estudiante:
"Personaliza la página. Cambia el título, modifica la lista y cambia el texto del párrafo."

Ahora hablemos de una recomendación importante: el orden.

Un código ordenado se entiende mejor. Por ejemplo, esto funciona, pero se ve desordenado:

<h1>Hola</h1><p>Texto</p><ul><li>Uno</li><li>Dos</li></ul>

En cambio, esto es más claro:

<h1>Hola</h1>

<p>Texto</p>

<ul>
    <li>Uno</li>
    <li>Dos</li>
</ul>

Es el mismo contenido, pero el segundo ejemplo es más fácil de leer.

Para cerrar esta lección:
Los encabezados organizan títulos.
Los párrafos muestran texto.
Las listas agrupan elementos.
Las imágenes agregan contenido visual.
Los enlaces permiten navegar a otras páginas.

RESUMEN EN PANTALLA:
- <h1> a <h6>: encabezados
- <p>: párrafos
- <ul>, <ol>, <li>: listas
- <img>: imágenes
- <a>: enlaces

============================================================
LECCIÓN 5 - INTRODUCCIÓN A CSS
RESPONSABLE INTERNO: RAFAEL
DURACIÓN: 8 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante entienda qué es CSS y cómo funcionan selectores, propiedades y valores.

EN PANTALLA:
Título: "Lección 5: Introducción a CSS"

GUION:

Ahora que ya sabemos crear contenido con HTML, vamos a aprender a darle estilo usando CSS.

CSS significa Cascading Style Sheets. En español podemos entenderlo como hojas de estilo en cascada.

CSS sirve para cambiar la apariencia de una página web. Gracias a CSS podemos modificar colores, fondos, tipos de letra, tamaños, bordes, espacios y posiciones.

Recordemos la comparación de la casa:
HTML es la estructura.
CSS es la decoración.

Si HTML coloca un título, CSS puede cambiar su color.
Si HTML coloca una imagen, CSS puede cambiar su tamaño.
Si HTML coloca una caja, CSS puede agregarle borde, fondo y espacio.

Veamos un ejemplo.

En HTML tenemos:

<h1>Mi página web</h1>
<p>Estoy aprendiendo CSS.</p>

Ahora en CSS escribimos:

h1 {
    color: blue;
}

Esto significa que el título h1 será de color azul.

Vamos a explicar la estructura de CSS.

h1 es el selector. El selector indica qué elemento queremos modificar.

color es la propiedad. La propiedad indica qué característica queremos cambiar.

blue es el valor. El valor indica cómo queremos cambiar esa característica.

Entonces CSS tiene esta forma:

selector {
    propiedad: valor;
}

ACCIÓN EN PANTALLA:
Mostrar la estructura con flechas:
selector -> h1
propiedad -> color
valor -> blue

Ahora probemos otras propiedades.

p {
    color: gray;
    font-size: 18px;
}

Aquí estamos diciendo que todos los párrafos tendrán color gris y tamaño de letra de 18 píxeles.

Ahora vamos a usar el body.

body {
    background-color: lightblue;
    font-family: Arial, sans-serif;
}

El body representa el cuerpo de la página. Si aplicamos estilos al body, afectamos a toda la página.

background-color cambia el color de fondo.
font-family cambia el tipo de letra.

PRÁCTICA GUIADA:
En CodePen, en HTML escribimos:

<h1>Mi página con CSS</h1>
<p>Esta página ya tiene estilos.</p>

En CSS escribimos:

body {
    background-color: lightblue;
    font-family: Arial, sans-serif;
}

h1 {
    color: navy;
}

p {
    color: darkslategray;
    font-size: 18px;
}

Ahora observamos cómo cambia la página. Antes se veía simple. Ahora tiene fondo, colores y una fuente diferente.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Cambia el color del título. Puedes probar red, green, purple o orange."

Continuamos.

CSS también permite seleccionar varios elementos. Por ejemplo:

h1, h2 {
    color: purple;
}

Esto aplicará el color morado a h1 y h2.

También podemos usar clases. Una clase sirve para aplicar estilos a elementos específicos.

En HTML:

<div class="tarjeta">
    <h1>Mi perfil</h1>
    <p>Estoy aprendiendo desarrollo web.</p>
</div>

Aquí tenemos un div con la clase tarjeta.

Un div es como una caja o contenedor que agrupa elementos.

En CSS, para seleccionar una clase, usamos un punto antes del nombre:

.tarjeta {
    background-color: white;
    border: 2px solid black;
}

Esto aplicará el estilo solamente a los elementos que tengan class="tarjeta".

ACCIÓN EN PANTALLA:
Escribir el div con class="tarjeta".
Luego escribir .tarjeta en CSS.
Mostrar cómo aparece la caja.

Ahora hablemos de comentarios. En CSS podemos escribir comentarios para explicar el código:

/* Este estilo cambia el fondo de la página */
body {
    background-color: lightblue;
}

Los comentarios no se muestran en la página. Solo sirven para que el código sea más entendible.

Para cerrar esta lección, recordemos:
CSS sirve para darle estilo a HTML.
CSS usa selectores, propiedades y valores.
El selector indica qué se modifica.
La propiedad indica qué característica cambia.
El valor indica cómo cambia.
Las clases permiten aplicar estilos a elementos específicos.

RESUMEN EN PANTALLA:
selector {
    propiedad: valor;
}

Ejemplo:
h1 {
    color: blue;
}

============================================================
LECCIÓN 6 - ESTILO SIMPLE CON CSS
RESPONSABLE INTERNO: RAFAEL
DURACIÓN: 7 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Que el estudiante aplique estilos simples: centrar contenido, añadir colores, bordes, márgenes y espacios.

EN PANTALLA:
Título: "Lección 6: Estilo simple con CSS"

GUION:

En esta lección vamos a mejorar el diseño de una página usando estilos simples.

Vamos a practicar con una caja o tarjeta. Esta tarjeta tendrá fondo, borde, espacio interno y estará centrada.

Primero escribimos este HTML:

<div class="tarjeta">
    <h1>Mi tarjeta</h1>
    <p>Estoy practicando estilos con CSS.</p>
</div>

Ahora vamos a escribir CSS paso a paso.

Primero cambiamos el estilo general de la página:

body {
    font-family: Arial, sans-serif;
    background-color: #e8f0fe;
    text-align: center;
}

Explicación:
font-family cambia la fuente.
background-color cambia el color de fondo.
text-align: center centra el texto.

Ahora damos estilo a la tarjeta:

.tarjeta {
    background-color: white;
    border: 2px solid #333;
    padding: 20px;
    margin: 40px auto;
    width: 50%;
}

Explicación:
background-color: white coloca fondo blanco.
border agrega un borde.
padding crea espacio interno.
margin crea espacio externo.
width define el ancho.
auto ayuda a centrar horizontalmente cuando se usa con margin.

ACCIÓN EN PANTALLA:
Mostrar la tarjeta antes de CSS.
Luego agregar CSS línea por línea.
Después de cada línea, mostrar el cambio.

Ahora agregamos bordes redondeados:

.tarjeta {
    border-radius: 10px;
}

Pero en vez de repetir la clase, lo colocamos dentro de la misma regla:

.tarjeta {
    background-color: white;
    border: 2px solid #333;
    border-radius: 10px;
    padding: 20px;
    margin: 40px auto;
    width: 50%;
}

Ahora la tarjeta se ve más moderna.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Cambia el color de fondo de la página. Prueba con #fce4ec, #e0f7fa o #fff9c4."

Continuamos.

Ahora vamos a mejorar una imagen.

En HTML agregamos:

<img src="https://via.placeholder.com/150" alt="Foto de perfil">

En CSS escribimos:

img {
    width: 150px;
    border-radius: 50%;
}

Explicación:
width cambia el tamaño.
border-radius: 50% hace que la imagen se vea circular.

Ahora agreguemos un botón usando un enlace. En HTML:

<a href="https://www.google.com">Buscar información</a>

En CSS:

a {
    color: white;
    background-color: #1976d2;
    padding: 10px 15px;
    border-radius: 8px;
    text-decoration: none;
}

Explicación:
color cambia el color del texto.
background-color cambia el fondo del enlace.
padding crea espacio interno.
border-radius redondea esquinas.
text-decoration: none quita el subrayado.

ACCIÓN EN PANTALLA:
Mostrar cómo el enlace se transforma en un botón simple.

Ahora hablemos de diseño limpio. Cuando estamos empezando, es recomendable no usar demasiados colores. Es mejor usar uno o dos colores principales y mantener el diseño ordenado.

También debemos cuidar que el texto se pueda leer. Por ejemplo, si usamos fondo oscuro, el texto debe ser claro. Si usamos fondo claro, el texto debe ser oscuro.

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Modifica el color del botón y revisa si el texto se lee bien."

Para cerrar esta lección:
Aprendimos a centrar contenido.
Agregamos color de fondo.
Creamos una tarjeta con borde.
Agregamos espacio interno y externo.
Redondeamos bordes.
Convertimos un enlace en un botón simple.

RESUMEN EN PANTALLA:
- text-align: center;
- background-color
- border
- padding
- margin
- width
- border-radius

============================================================
LECCIÓN 7 - PROYECTO FINAL: PÁGINA DE PERFIL
RESPONSABLE INTERNO: ENRIQUE
DURACIÓN: 10 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Crear una página web básica de perfil personal usando HTML y CSS.

EN PANTALLA:
Título: "Lección 7: Proyecto final - Página de perfil"

GUION:

Ahora vamos a unir todo lo aprendido para crear nuestro proyecto final: una página de perfil personal.

Esta página tendrá:
Un título.
Una imagen.
Una descripción.
Una lista de habilidades o gustos.
Un enlace con estilo de botón.
Diseño con CSS.

La idea es que cada estudiante pueda personalizar la página con su propio nombre, gustos y colores.

Primero vamos a escribir el HTML.

En la sección HTML del editor online escribimos:

<div class="perfil">
    <h1>Mi perfil personal</h1>

    <img src="https://via.placeholder.com/150" alt="Foto de perfil">

    <p>
        Hola, soy estudiante y estoy aprendiendo desarrollo web.
        Esta es mi primera página usando HTML y CSS.
    </p>

    <h2>Mis habilidades</h2>

    <ul>
        <li>Crear títulos y párrafos</li>
        <li>Agregar imágenes</li>
        <li>Usar listas y enlaces</li>
        <li>Dar estilo con CSS</li>
    </ul>

    <a href="https://www.google.com">Buscar más información</a>
</div>

Ahora expliquemos el código.

Usamos un div con la clase perfil. El div funciona como un contenedor. Es como una caja donde colocamos todo el contenido de nuestro perfil.

Dentro del contenedor tenemos un h1. Este es el título principal de la página.

Luego tenemos una imagen con img. Usamos src para indicar la imagen y alt para describirla.

Después tenemos un párrafo con p. Este párrafo contiene una pequeña presentación.

Luego tenemos un h2 para el subtítulo "Mis habilidades".

Después usamos una lista desordenada con ul y varios elementos li.

Finalmente usamos un enlace con a. Más adelante, con CSS, este enlace se verá como un botón.

ACCIÓN EN PANTALLA:
Escribir el HTML en vivo, no pegarlo todo de golpe.
Después de cada bloque, mostrar el resultado:
- Primero h1
- Luego imagen
- Luego párrafo
- Luego lista
- Luego enlace

PAUSA DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Antes de continuar, cambia el título por el nombre de tu propia página. Por ejemplo: Perfil de Ana, Mi blog o Página de Carlos."

Continuamos.

Ahora vamos a escribir el CSS.

En la sección CSS escribimos:

body {
    font-family: Arial, sans-serif;
    background-color: #e8f0fe;
    text-align: center;
}

.perfil {
    background-color: white;
    border: 2px solid #333;
    border-radius: 10px;
    width: 50%;
    margin: 40px auto;
    padding: 20px;
}

img {
    width: 150px;
    border-radius: 50%;
}

ul {
    text-align: left;
    display: inline-block;
}

a {
    color: white;
    background-color: #1976d2;
    padding: 10px 15px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
}

Ahora explicamos cada parte.

En body usamos una fuente sencilla, un fondo claro y centramos el texto.

En .perfil damos estilo al contenedor principal. Le colocamos fondo blanco, borde, esquinas redondeadas, ancho, margen y espacio interno.

En img ajustamos el tamaño de la imagen y la hacemos circular.

En ul usamos text-align: left para que la lista se lea ordenadamente, aunque el resto de la página esté centrado. display: inline-block ayuda a que la lista se mantenga agrupada.

En a convertimos el enlace en un botón visual. Le damos color de texto blanco, fondo azul, espacio interno, bordes redondeados y quitamos el subrayado.

ACCIÓN EN PANTALLA:
Aplicar el CSS poco a poco.
Mostrar el cambio visual después de cada bloque.

PAUSA DE PRÁCTICA 2 MINUTOS:
Pedir al estudiante:
"Personaliza la página. Cambia tres cosas:
1. El título.
2. La lista de habilidades.
3. El color de fondo."

Ejemplos para cambiar el color de fondo:

body {
    background-color: #fce4ec;
}

body {
    background-color: #e0f7fa;
}

body {
    background-color: #fff9c4;
}

Continuamos.

Ahora vamos a revisar la página final.

Debemos comprobar:
¿El título aparece correctamente?
¿La imagen carga?
¿El párrafo se lee bien?
¿La lista está ordenada?
¿El enlace funciona?
¿Los colores se ven bien?
¿El diseño está centrado?

Si algo no funciona, no hay problema. En desarrollo web los errores son normales. Lo importante es revisar con calma.

Ahora mostraremos el código completo del proyecto final. Este código puede guardarse como ejemplo terminado en el repositorio de GitHub del curso.

CÓDIGO HTML FINAL PARA CODEPEN:

<div class="perfil">
    <h1>Mi perfil personal</h1>

    <img src="https://via.placeholder.com/150" alt="Foto de perfil">

    <p>
        Hola, soy estudiante y estoy aprendiendo desarrollo web.
        Esta es mi primera página usando HTML y CSS.
    </p>

    <h2>Mis habilidades</h2>

    <ul>
        <li>Crear títulos y párrafos</li>
        <li>Agregar imágenes</li>
        <li>Usar listas y enlaces</li>
        <li>Dar estilo con CSS</li>
    </ul>

    <a href="https://www.google.com">Buscar más información</a>
</div>

CÓDIGO CSS FINAL PARA CODEPEN:

body {
    font-family: Arial, sans-serif;
    background-color: #e8f0fe;
    text-align: center;
}

.perfil {
    background-color: white;
    border: 2px solid #333;
    border-radius: 10px;
    width: 50%;
    margin: 40px auto;
    padding: 20px;
}

img {
    width: 150px;
    border-radius: 50%;
}

ul {
    text-align: left;
    display: inline-block;
}

a {
    color: white;
    background-color: #1976d2;
    padding: 10px 15px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
}

Para cerrar esta lección, ya tenemos una página de perfil personal. Este proyecto usa los conceptos principales del curso: etiquetas HTML, atributos, listas, imágenes, enlaces, selectores CSS, colores, bordes, espacios y alineación.

============================================================
LECCIÓN 8 - RECOMENDACIONES Y ERRORES COMUNES
RESPONSABLE INTERNO: ENRIQUE
DURACIÓN: 5 MINUTOS
============================================================

OBJETIVO DE LA LECCIÓN:
Reforzar buenas prácticas y mostrar errores frecuentes de principiantes.

EN PANTALLA:
Título: "Lección 8: Recomendaciones y errores comunes"

GUION:

Para terminar el curso, veremos algunas recomendaciones y errores comunes que suelen aparecer cuando estamos empezando con HTML y CSS.

Primera recomendación: escribe el código de forma ordenada.

Un código ordenado es más fácil de leer, corregir y mejorar. Usa saltos de línea, espacios y nombres claros.

No recomendado:

<h1>Hola</h1><p>Texto</p><ul><li>Uno</li><li>Dos</li></ul>

Mejor:

<h1>Hola</h1>

<p>Texto</p>

<ul>
    <li>Uno</li>
    <li>Dos</li>
</ul>

Segunda recomendación: usa nombres claros para las clases.

Por ejemplo, es mejor usar:

class="perfil"

o:

class="tarjeta"

En lugar de nombres confusos como:

class="caja1"

o:

class="x"

Tercera recomendación: prueba los cambios poco a poco. Si escribes muchas líneas de código y algo falla, será más difícil encontrar el error.

Cuarta recomendación: revisa que las imágenes y enlaces funcionen correctamente.

Ahora veamos errores comunes.

ERROR 1: Olvidar cerrar etiquetas.

Incorrecto:

<p>Estoy aprendiendo HTML

Correcto:

<p>Estoy aprendiendo HTML</p>

ERROR 2: Escribir mal una etiqueta.

Incorrecto:

<hi>Mi título</hi>

Correcto:

<h1>Mi título</h1>

ERROR 3: Olvidar comillas en los atributos.

No recomendado:

<img src=foto.jpg alt=Foto de perfil>

Correcto:

<img src="foto.jpg" alt="Foto de perfil">

ERROR 4: Confundir HTML con CSS.

HTML estructura el contenido:

<h1>Mi página</h1>

CSS diseña el contenido:

h1 {
    color: blue;
}

ERROR 5: Olvidar punto y coma en CSS.

Incorrecto:

h1 {
    color: blue
    font-size: 30px;
}

Correcto:

h1 {
    color: blue;
    font-size: 30px;
}

ERROR 6: Usar colores que no dejan leer.

Por ejemplo, texto amarillo sobre fondo blanco puede ser difícil de leer. Debemos elegir colores con buen contraste.

PAUSA FINAL DE PRÁCTICA 1 MINUTO:
Pedir al estudiante:
"Revisa tu página final. Comprueba si el título, la imagen, la lista, el enlace y los estilos funcionan correctamente."

Ahora cerremos el curso.

Hoy aprendimos que un sitio web se puede ver desde un navegador. También aprendimos que HTML sirve para organizar el contenido y CSS sirve para darle diseño.

Usamos encabezados, párrafos, listas, imágenes y enlaces. También aplicamos estilos como colores, fuentes, bordes, espacios y alineación.

Finalmente, creamos una página web básica de perfil personal.

Este es solo el primer paso. Después de dominar HTML y CSS, se puede aprender JavaScript para agregar más interacción, como botones, formularios y efectos dinámicos.

Gracias por completar este curso de fundamentos de desarrollo web.

RESUMEN FINAL EN PANTALLA:
- HTML = estructura
- CSS = diseño
- Proyecto final = página de perfil
- Practica modificando textos, colores e imágenes
- Sigue aprendiendo paso a paso

============================================================
ANEXO 1 - CÓDIGO FINAL EN FORMATO HTML COMPLETO
============================================================

Este formato sirve si el equipo quiere guardar un archivo index.html completo en GitHub.
En CodePen, normalmente se separa HTML y CSS, pero para GitHub pueden guardar este archivo completo:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mi perfil personal</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e8f0fe;
            text-align: center;
        }

        .perfil {
            background-color: white;
            border: 2px solid #333;
            border-radius: 10px;
            width: 50%;
            margin: 40px auto;
            padding: 20px;
        }

        img {
            width: 150px;
            border-radius: 50%;
        }

        ul {
            text-align: left;
            display: inline-block;
        }

        a {
            color: white;
            background-color: #1976d2;
            padding: 10px 15px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="perfil">
        <h1>Mi perfil personal</h1>

        <img src="https://via.placeholder.com/150" alt="Foto de perfil">

        <p>
            Hola, soy estudiante y estoy aprendiendo desarrollo web.
            Esta es mi primera página usando HTML y CSS.
        </p>

        <h2>Mis habilidades</h2>

        <ul>
            <li>Crear títulos y párrafos</li>
            <li>Agregar imágenes</li>
            <li>Usar listas y enlaces</li>
            <li>Dar estilo con CSS</li>
        </ul>

        <br><br>

        <a href="https://www.google.com">Buscar más información</a>
    </div>
</body>
</html>

============================================================
ANEXO 2 - PLANTILLA PARA LA DESCRIPCIÓN DE CADA VIDEO EN YOUTUBE
============================================================

Título del video:
Lección [número]: [nombre de la lección] - Fundamentos de Desarrollo Web

Descripción:
En esta lección aprenderás [resumen breve de la lección].
No necesitas instalar programas. Solo usarás tu navegador web.

Práctica online:
[Pegar enlace de CodePen, JSFiddle o Replit]

Repositorio de código:
[Pegar enlace del repositorio público de GitHub]

Contenido:
00:00 Introducción
00:30 Explicación del tema
03:00 Demostración en editor online
06:00 Práctica guiada
08:00 Resumen

============================================================
ANEXO 3 - CHECKLIST DE ENTREGA DEL EQUIPO
============================================================

Antes de entregar, revisar:

[ ] El curso completo dura aproximadamente 1 hora.
[ ] Está dividido en 5 a 10 lecciones.
[ ] Cada lección dura entre 5 y 15 minutos.
[ ] El público objetivo es secundaria, de 12 a 17 años.
[ ] El lenguaje es sencillo y progresivo.
[ ] No se pide instalar herramientas.
[ ] Se usa CodePen, JSFiddle o Replit.
[ ] Los videos están subidos como no listados en YouTube.
[ ] Cada video tiene enlace a la práctica online.
[ ] El código fuente está en un repositorio público de GitHub.
[ ] El repositorio tiene README.md.
[ ] El repositorio incluye carpetas /starter-files, /completed-examples y /scripts.
[ ] El informe está en Markdown.
[ ] El Markdown incluye resumen del curso.
[ ] El Markdown incluye secuencia de lecciones.
[ ] El Markdown incluye enlaces a YouTube.
[ ] El Markdown incluye enlace al repositorio.
[ ] El Markdown incluye enlaces directos a editores online.
[ ] El Markdown incluye resumen de elaboración en equipo.
[ ] No se usan nombres de autores ni branding en el contenido del video o código fuente.
[ ] El audio se escucha claro.
[ ] El código se ve legible en pantalla.
[ ] Se incluyen pausas de práctica.
[ ] Se evitan palabras demasiado técnicas.
[ ] Se revisaron errores comunes antes de grabar.

============================================================
ANEXO 4 - GUÍA PARA QUE REALMENTE DURE 1 HORA
============================================================

No lean el guion de corrido. El formato correcto para cada lección es:

1. Presentar el objetivo de la lección.
2. Explicar el concepto con una comparación sencilla.
3. Mostrar el código en pantalla.
4. Escribir el código lentamente.
5. Explicar cada línea.
6. Mostrar el resultado.
7. Dar una pausa de práctica.
8. Hacer un resumen breve.

Si el video queda corto, agreguen estas acciones:
- Preguntar al estudiante qué cree que pasará antes de ejecutar el código.
- Mostrar un error común y corregirlo.
- Cambiar un color o texto en vivo.
- Comparar antes y después.
- Repetir los conceptos clave con ejemplos diferentes.

Tiempo sugerido por integrante:
Davicho:
Lección 1 = 7 minutos
Lección 2 = 8 minutos
Total = 15 minutos

Sofía:
Lección 3 = 7 minutos
Lección 4 = 8 minutos
Total = 15 minutos

Rafael:
Lección 5 = 8 minutos
Lección 6 = 7 minutos
Total = 15 minutos

Enrique:
Lección 7 = 10 minutos
Lección 8 = 5 minutos
Total = 15 minutos

TOTAL GENERAL = 60 MINUTOS
