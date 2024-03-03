Aquí tienes una guía más completa de los elementos de HTML semántico que son esenciales para el desarrollo web:

| Elemento | Ejemplo | Características | Consejos |
| -------- | ------- | --------------- | -------- |
| `<header>` | `<header><h1>Título del sitio web</h1></header>` | Se utiliza para contener la introducción o navegación del sitio web. | No confundir con `<head>`, que se utiliza para metadatos y no se muestra en la página web. |
| `<nav>` | `<nav><a href="#">Inicio</a></nav>` | Se utiliza para contener los enlaces de navegación del sitio web. | No todos los enlaces deben estar en un `<nav>`. Solo los enlaces de navegación principal deben estar aquí. |
| `<main>` | `<main><p>Este es el contenido principal.</p></main>` | Se utiliza para contener el contenido principal del sitio web. | Debe haber solo un `<main>` por página y no debe estar dentro de `<article>`, `<aside>`, `<footer>`, `<header>` o `<nav>`. |
| `<article>` | `<article><p>Este es un artículo.</p></article>` | Se utiliza para contener un bloque de contenido independiente que tiene sentido por sí mismo. | `<article>` es para contenido que tiene sentido por sí solo, como un post de blog. `<section>` es para contenido relacionado. |
| `<section>` | `<section><p>Esta es una sección.</p></section>` | Se utiliza para agrupar contenido relacionado. | `<section>` es para contenido relacionado. `<div>` es para agrupar elementos por razones estilísticas o por script. |
| `<aside>` | `<aside><p>Este es un contenido secundario.</p></aside>` | Se utiliza para contener contenido que está relacionado con el contenido principal, pero puede estar separado. | `<aside>` es para contenido secundario o tangencial. No debe contener contenido principal. |
| `<figure>` y `<figcaption>` | `<figure><img src="imagen.jpg"><figcaption>Esta es una imagen.</figcaption></figure>` | `<figure>` se utiliza para contener contenido relacionado, como imágenes, diagramas, fotos, código, etc. `<figcaption>` se utiliza para proporcionar una descripción o leyenda para el contenido de `<figure>`. | `<figure>` y `<figcaption>` deben usarse juntos. |
| `<footer>` | `<footer><p>&copy; 2024 Mi sitio web</p></footer>` | Se utiliza para contener la información del pie de página del sitio web. | `<footer>` es para información de pie de página, como información de contacto o derechos de autor. No debe contener contenido principal. |
| `<time>` | `<time datetime="2024-02-17">17 de Febrero, 2024</time>` | Se utiliza para representar una fecha o hora específica. | El atributo `datetime` debe ser una fecha o hora válida según el estándar ISO 8601. |
| `<mark>` | `<p>El <mark>HTML semántico</mark> es importante.</p>` | Se utiliza para resaltar una parte del texto. | `<mark>` es para resaltar texto en su contexto actual. No debe usarse para estilizar texto. |
| `<details>` y `<summary>` | `<details><summary>Ver más</summary><p>Este es el contenido detallado.</p></details>` | `<details>` se utiliza para crear un widget de divulgación que oculta contenido. `<summary>` se utiliza para proporcionar un título o resumen al contenido de `<details>`. | `<details>` y `<summary>` deben usarse juntos. |

