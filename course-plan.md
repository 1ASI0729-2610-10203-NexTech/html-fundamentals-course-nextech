# Fundamentos de HTML y CSS para Principiantes

## Resumen del curso

Este curso de 1 hora introduce a estudiantes de secundaria a la creacion de sitios web sencillos usando HTML y CSS. **No requiere descargas ni instalaciones.** Solo se necesita un navegador web y acceso a un editor online gratuito.

- **Duracion total**: 60 minutos
- **Publico objetivo**: Estudiantes de 12 a 17 anos sin experiencia previa en programacion
- **Prerrequisitos**: Ninguno
- **Herramientas necesarias**: Navegador web (Chrome, Firefox, Safari o Edge), CodePen, JSFiddle o Replit
- **Repositorio de codigo fuente**: [https://github.com/1ASI0729-2610-10203-NexTech/html-fundamentals-course-nextech](https://github.com/1ASI0729-2610-10203-NexTech/html-fundamentals-course-nextech)
- **Guion completo**: [`scripts/full-video-script.md`](./scripts/full-video-script.md)

---

## Objetivo general

Que el estudiante comprenda los fundamentos del desarrollo web y pueda crear una pagina web basica usando HTML para organizar el contenido y CSS para darle estilo.

Al finalizar el curso, el estudiante podra:

- Explicar que es un sitio web y que rol cumplen HTML, CSS y JavaScript.
- Crear la estructura basica de un documento HTML.
- Usar etiquetas, elementos y atributos frecuentes.
- Agregar encabezados, parrafos, listas, imagenes y enlaces.
- Aplicar estilos simples con CSS usando selectores y propiedades.
- Construir una pagina de perfil personal con HTML y CSS.
- Identificar errores comunes y corregirlos con calma.

---

## Secuencia de lecciones

### Leccion 1: Que es un sitio web (7 minutos)

- **Dificultad**: Principiante absoluto
- **Descripcion**: Introduce que es un sitio web, como funciona el navegador y que papel cumplen HTML, CSS y JavaScript.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L1)
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L1)
- **Archivo starter**: [`starter-files/lesson01-intro-web.html`](./starter-files/lesson01-intro-web.html)
- **Archivo completo**: [`completed-examples/lesson01-intro-web.html`](./completed-examples/lesson01-intro-web.html)

#### Objetivos

Al finalizar esta leccion podras:

- Definir que es un sitio web con palabras sencillas.
- Reconocer el rol del navegador.
- Diferenciar HTML, CSS y JavaScript.
- Crear una primera prueba con un titulo y un parrafo.

#### Contenido

Un sitio web es un conjunto de paginas que se visitan desde internet usando un navegador. Ejemplos comunes son una pagina de noticias, una tienda online, un blog, una red social o una plataforma de videos.

HTML se usa para crear la estructura y el contenido. CSS se usa para dar diseno al contenido. JavaScript agrega interaccion.

| Tecnologia | Funcion principal |
|---|---|
| HTML | Estructura y contenido |
| CSS | Diseno visual |
| JavaScript | Interaccion |

Ejemplo inicial:

```html
<h1>Hola mundo</h1>
<p>Estoy aprendiendo desarrollo web.</p>
```

#### Practica

Abre CodePen o tu editor online favorito y escribe el ejemplo anterior. Observa como aparece un titulo grande y un parrafo en el resultado.

#### Conclusiones clave

- Un sitio web se abre con un navegador.
- HTML organiza el contenido.
- CSS mejora el diseno visual.
- En este curso se trabajara principalmente con HTML y CSS.

---

### Leccion 2: Primera estructura HTML (8 minutos)

- **Dificultad**: Principiante
- **Descripcion**: Presenta la estructura minima de una pagina HTML y explica para que sirven `<!DOCTYPE html>`, `<html>`, `<head>` y `<body>`.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L2)
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L2)
- **Archivo starter**: [`starter-files/lesson02-html-structure.html`](./starter-files/lesson02-html-structure.html)
- **Archivo completo**: [`completed-examples/lesson02-html-structure.html`](./completed-examples/lesson02-html-structure.html)

#### Objetivos

Al finalizar esta leccion podras:

- Identificar la estructura basica de un archivo HTML.
- Entender la diferencia entre la informacion del documento y el contenido visible.
- Escribir contenido dentro de `<body>`.
- Reconocer que CodePen permite trabajar directamente con el contenido visible.

#### Contenido

HTML significa HyperText Markup Language. Un documento HTML completo tiene una estructura como esta:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mi primera pagina</title>
  </head>
  <body>
    <h1>Mi primera pagina web</h1>
    <p>Estoy aprendiendo HTML.</p>
  </body>
</html>
```

| Parte | Funcion |
|---|---|
| `<!DOCTYPE html>` | Indica que el documento usa HTML moderno |
| `<html>` | Contiene toda la pagina |
| `<head>` | Guarda informacion para el navegador |
| `<title>` | Define el titulo de la pestana |
| `<body>` | Contiene lo que el usuario ve |

En CodePen normalmente se escribe solo el contenido que iria dentro de `<body>`:

```html
<h1>Mi primera pagina web</h1>
<p>Estoy aprendiendo HTML.</p>
```

#### Practica

Escribe una pagina pequena con un titulo y dos parrafos. Cambia el texto para que hable sobre ti o sobre un tema que te guste.

#### Conclusiones clave

- HTML tiene una estructura ordenada.
- El contenido visible va dentro de `<body>`.
- CodePen simplifica el trabajo porque prepara parte de la estructura.

---

### Leccion 3: Etiquetas, elementos y atributos (11:18 minutos)

- **Dificultad**: Basico
- **Descripcion**: Explica la diferencia entre etiqueta, elemento y atributo usando ejemplos con parrafos, enlaces e imagenes.
- **Enlace de YouTube**: https://youtu.be/aWG9XW4Cwr0
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L3)
- **Archivo starter**: [`starter-files/lesson03-tags-elements-attributes.html`](./starter-files/lesson03-tags-elements-attributes.html)
- **Archivo completo**: [`completed-examples/lesson03-tags-elements-attributes.html`](./completed-examples/lesson03-tags-elements-attributes.html)

#### Objetivos

Al finalizar esta leccion podras:

- Diferenciar etiqueta, elemento y atributo.
- Crear enlaces con `href`.
- Insertar imagenes con `src` y `alt`.
- Evitar errores comunes al escribir atributos.

#### Contenido

Una etiqueta es la marca que indica al navegador que tipo de contenido se esta usando. Un elemento incluye la etiqueta de apertura, el contenido y la etiqueta de cierre.

```html
<p>Este es un parrafo.</p>
```

Un atributo agrega informacion extra a una etiqueta. Por ejemplo, un enlace usa `href` para indicar a donde llevara al usuario:

```html
<a href="https://www.google.com">Ir a Google</a>
```

Una imagen usa `src` para indicar la ruta de la imagen y `alt` para describirla:

```html
<img src="https://via.placeholder.com/150" alt="Imagen de ejemplo">
```

#### Practica

Crea un titulo, un parrafo y un enlace. Luego cambia el texto del enlace por una frase propia, como "Buscar informacion".

#### Conclusiones clave

- Las etiquetas indican el tipo de contenido.
- Los elementos son estructuras completas.
- Los atributos dan informacion adicional.
- Los valores de atributos deben escribirse entre comillas.

---

### Leccion 4: Elementos HTML comunes (11:17 minutos)

- **Dificultad**: Basico
- **Descripcion**: Presenta encabezados, parrafos, listas, imagenes y enlaces para crear una pagina sencilla.
- **Enlace de YouTube**: https://youtu.be/lsmOu3zXPJk
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L4)
- **Archivo starter**: [`starter-files/lesson04-common-elements.html`](./starter-files/lesson04-common-elements.html)
- **Archivo completo**: [`completed-examples/lesson04-common-elements.html`](./completed-examples/lesson04-common-elements.html)

#### Objetivos

Al finalizar esta leccion podras:

- Usar encabezados para ordenar informacion.
- Crear parrafos descriptivos.
- Escribir listas ordenadas y no ordenadas.
- Agregar imagenes y enlaces.

#### Contenido

Los elementos HTML mas frecuentes permiten construir la base de una pagina:

| Elemento | Uso |
|---|---|
| `<h1>` a `<h6>` | Encabezados |
| `<p>` | Parrafos |
| `<ul>` y `<ol>` | Listas |
| `<li>` | Elementos de lista |
| `<img>` | Imagenes |
| `<a>` | Enlaces |

Ejemplo de pagina sencilla:

```html
<h1>Mi perfil</h1>
<p>Hola, estoy aprendiendo desarrollo web.</p>

<h2>Mis intereses</h2>
<ul>
  <li>Tecnologia</li>
  <li>Musica</li>
  <li>Deportes</li>
</ul>

<img src="https://via.placeholder.com/200" alt="Imagen de perfil">
<a href="https://www.google.com">Google</a>
```

#### Practica

Crea una mini pagina de perfil con tu nombre, una descripcion, una lista de intereses, una imagen y un enlace.

#### Conclusiones clave

- Los encabezados ordenan la informacion.
- Las listas sirven para agrupar elementos.
- Las imagenes necesitan `src` y `alt`.
- Los enlaces permiten navegar a otras paginas.

---

### Leccion 5: Introduccion a CSS (8 minutos)

- **Dificultad**: Basico
- **Descripcion**: Explica que es CSS, como se conecta con HTML y como se usan selectores y propiedades.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L5)
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L5)
- **Archivo starter**: [`starter-files/lesson05-intro-css.html`](./starter-files/lesson05-intro-css.html)
- **Archivo completo**: [`completed-examples/lesson05-intro-css.html`](./completed-examples/lesson05-intro-css.html)

#### Objetivos

Al finalizar esta leccion podras:

- Explicar para que sirve CSS.
- Usar selectores basicos.
- Aplicar propiedades como color, tamano de texto, fondo y alineacion.
- Separar contenido HTML de presentacion CSS.

#### Contenido

CSS significa Cascading Style Sheets. Sirve para definir como se ve el contenido HTML.

```css
h1 {
  color: blue;
  font-size: 32px;
}

p {
  color: gray;
}
```

| Concepto | Ejemplo | Funcion |
|---|---|---|
| Selector | `h1` | Elige el elemento |
| Propiedad | `color` | Indica que se cambia |
| Valor | `blue` | Define el resultado |

Ejemplo combinado en CodePen:

```html
<h1>Mi pagina con CSS</h1>
<p>Ahora mi contenido tiene estilo.</p>
```

```css
body {
  background-color: #f2f2f2;
  font-family: Arial, sans-serif;
}

h1 {
  color: #1e88e5;
}
```

#### Practica

Cambia el color del titulo, el color de fondo de la pagina y la fuente del texto.

#### Conclusiones clave

- HTML crea el contenido.
- CSS define la apariencia.
- Un selector permite elegir que elemento se va a modificar.
- Las reglas CSS se escriben con propiedad y valor.

---

### Leccion 6: Estilo simple con CSS (7 minutos)

- **Dificultad**: Basico
- **Descripcion**: Aplica estilos simples para mejorar una pagina: centrado, colores, bordes, espacios y botones.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L6)
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L6)
- **Archivo starter**: [`starter-files/lesson06-simple-styles.html`](./starter-files/lesson06-simple-styles.html)
- **Archivo completo**: [`completed-examples/lesson06-simple-styles.html`](./completed-examples/lesson06-simple-styles.html)

#### Objetivos

Al finalizar esta leccion podras:

- Centrar contenido con CSS.
- Aplicar fondos, bordes y espacios.
- Dar estilo a una imagen.
- Transformar un enlace en un boton visual.

#### Contenido

CSS permite que una pagina sea mas clara y agradable. Por ejemplo:

```css
body {
  font-family: Arial, sans-serif;
  background-color: #eef4ff;
  text-align: center;
}

.card {
  background-color: white;
  border: 2px solid #1e88e5;
  border-radius: 10px;
  padding: 20px;
  max-width: 400px;
  margin: 30px auto;
}

a {
  display: inline-block;
  background-color: #1e88e5;
  color: white;
  padding: 10px 15px;
  border-radius: 6px;
  text-decoration: none;
}
```

#### Practica

Agrega una tarjeta de perfil, centra el contenido, cambia el fondo y convierte un enlace en boton.

#### Conclusiones clave

- `text-align` ayuda a alinear texto.
- `margin` y `padding` controlan espacios.
- `border` y `border-radius` ayudan a crear tarjetas.
- Un enlace puede verse como boton con CSS.

---

### Leccion 7: Proyecto final - Pagina de perfil (10 minutos)

- **Dificultad**: Intermedio inicial
- **Descripcion**: Integra HTML y CSS para construir una pagina de perfil personal completa.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L7)
- **Proyecto online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L7)
- **Archivo starter**: [`starter-files/lesson07-final-profile-page.html`](./starter-files/lesson07-final-profile-page.html)
- **Archivo completo**: [`completed-examples/lesson07-final-profile-page.html`](./completed-examples/lesson07-final-profile-page.html)

#### Objetivos

Al finalizar esta leccion podras:

- Construir una pagina de perfil personal.
- Combinar etiquetas HTML con estilos CSS.
- Organizar una imagen, una lista y un enlace.
- Revisar que el resultado se vea ordenado.

#### Contenido

Codigo HTML base del proyecto:

```html
<div class="card">
  <h1>Mi perfil</h1>
  <img src="https://via.placeholder.com/150" alt="Foto de perfil">
  <p>Hola, soy estudiante y estoy aprendiendo desarrollo web.</p>

  <h2>Mis intereses</h2>
  <ul>
    <li>Crear paginas web</li>
    <li>Aprender HTML</li>
    <li>Usar listas y enlaces</li>
  </ul>

  <a href="https://www.google.com">Buscar mas informacion</a>
</div>
```

Codigo CSS base del proyecto:

```css
body {
  font-family: Arial, sans-serif;
  background-color: #eef4ff;
  text-align: center;
}

.card {
  background-color: white;
  max-width: 400px;
  margin: 30px auto;
  padding: 20px;
  border-radius: 12px;
  border: 2px solid #1e88e5;
}

img {
  border-radius: 50%;
}
```

#### Practica

Personaliza la pagina con tu nombre, tus intereses, colores propios y un enlace que te parezca util.

#### Conclusiones clave

- El proyecto final une los conceptos principales del curso.
- Una pagina puede crecer paso a paso si se organiza bien.
- HTML y CSS trabajan juntos: contenido y presentacion.

---

### Leccion 8: Recomendaciones y errores comunes (5 minutos)

- **Dificultad**: Basico
- **Descripcion**: Revisa errores frecuentes de HTML y CSS, recomendaciones para principiantes y proximos pasos.
- **Enlace de YouTube**: [Ver la leccion](https://youtu.be/REEMPLAZAR-L8)
- **Practica online**: [Abrir en CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L8)
- **Guion de apoyo**: [`scripts/lesson-08-recommendations-common-errors.md`](./scripts/lesson-08-recommendations-common-errors.md)

#### Objetivos

Al finalizar esta leccion podras:

- Revisar errores comunes al escribir HTML.
- Detectar problemas frecuentes en CSS.
- Confirmar que imagenes, enlaces y estilos funcionen.
- Saber que aprender despues del curso.

#### Contenido

Errores comunes:

| Error | Como evitarlo |
|---|---|
| No cerrar etiquetas | Revisar que cada etiqueta tenga apertura y cierre cuando corresponda |
| Escribir atributos sin comillas | Usar `href="..."` y `src="..."` |
| Olvidar `alt` en imagenes | Describir la imagen con texto breve |
| Confundir HTML y CSS | HTML va en la zona HTML, CSS en la zona CSS |
| No revisar enlaces | Probar cada enlace antes de entregar |

Buenas practicas:

- Usar nombres claros.
- Mantener el codigo ordenado.
- Avanzar paso a paso.
- Revisar el resultado en el navegador.
- Leer los mensajes de error con calma.

#### Practica

Revisa tu pagina final. Comprueba que el titulo, la imagen, la lista, el enlace y los estilos funcionen correctamente.

#### Conclusiones clave

- Los errores son parte normal del aprendizaje.
- Revisar con calma ayuda a encontrar fallas rapidamente.
- Despues de HTML y CSS, puedes aprender mas CSS, responsive design y JavaScript.

---

## Actividades practicas

| Leccion | Actividad | Editor online | Starter | Ejemplo completo |
|---:|---|---|---|---|
| 1 | Primer titulo y parrafo | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L1) | [`lesson01-intro-web.html`](./starter-files/lesson01-intro-web.html) | [`lesson01-intro-web.html`](./completed-examples/lesson01-intro-web.html) |
| 2 | Estructura HTML basica | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L2) | [`lesson02-html-structure.html`](./starter-files/lesson02-html-structure.html) | [`lesson02-html-structure.html`](./completed-examples/lesson02-html-structure.html) |
| 3 | Etiquetas y atributos | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L3) | [`lesson03-tags-elements-attributes.html`](./starter-files/lesson03-tags-elements-attributes.html) | [`lesson03-tags-elements-attributes.html`](./completed-examples/lesson03-tags-elements-attributes.html) |
| 4 | Elementos comunes | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L4) | [`lesson04-common-elements.html`](./starter-files/lesson04-common-elements.html) | [`lesson04-common-elements.html`](./completed-examples/lesson04-common-elements.html) |
| 5 | Primeros estilos CSS | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L5) | [`lesson05-intro-css.html`](./starter-files/lesson05-intro-css.html) | [`lesson05-intro-css.html`](./completed-examples/lesson05-intro-css.html) |
| 6 | Tarjeta con estilos | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L6) | [`lesson06-simple-styles.html`](./starter-files/lesson06-simple-styles.html) | [`lesson06-simple-styles.html`](./completed-examples/lesson06-simple-styles.html) |
| 7 | Pagina de perfil | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L7) | [`lesson07-final-profile-page.html`](./starter-files/lesson07-final-profile-page.html) | [`lesson07-final-profile-page.html`](./completed-examples/lesson07-final-profile-page.html) |
| 8 | Revision final | [CodePen](https://codepen.io/pen/?template=REEMPLAZAR-L8) | Proyecto final personalizado | Proyecto final personalizado |

---

## Enlaces de videos

| Leccion | Video de YouTube no listado |
|---:|---|
| 1 | [https://youtu.be/REEMPLAZAR-L1](https://youtu.be/REEMPLAZAR-L1) |
| 2 | [https://youtu.be/REEMPLAZAR-L2](https://youtu.be/REEMPLAZAR-L2) |
| 3 | [https://youtu.be/REEMPLAZAR-L3](https://youtu.be/REEMPLAZAR-L3) |
| 4 | [https://youtu.be/REEMPLAZAR-L4](https://youtu.be/REEMPLAZAR-L4) |
| 5 | [https://youtu.be/REEMPLAZAR-L5](https://youtu.be/REEMPLAZAR-L5) |
| 6 | [https://youtu.be/REEMPLAZAR-L6](https://youtu.be/REEMPLAZAR-L6) |
| 7 | [https://youtu.be/REEMPLAZAR-L7](https://youtu.be/REEMPLAZAR-L7) |
| 8 | [https://youtu.be/REEMPLAZAR-L8](https://youtu.be/REEMPLAZAR-L8) |

> Reemplazar cada enlace cuando los videos no listados esten publicados en YouTube.

---

## Recursos adicionales

- [MDN Web Docs - HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [CodePen](https://codepen.io/)
- [JSFiddle](https://jsfiddle.net/)
- [Replit](https://replit.com/)

---

## Elaboracion

- Universidad Peruana de Ciencias Aplicadas
- Carrera de Ingenieria de Software
- Periodo 202610
- Curso: 1ASI0730 Aplicaciones Web
- Equipo: NexTech
- Producto: Curso de fundamentos de HTML y CSS

**Responsables internos identificados en el guion**:

- Davicho: lecciones 1 y 2
- Sofia: lecciones 3 y 4
- Rafael: lecciones 5 y 6
- Enrique: lecciones 7 y 8

**Fecha de entrega**: Por completar
