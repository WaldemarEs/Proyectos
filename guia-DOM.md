¡Claro! Aquí tienes la guía actualizada de los elementos DOM con ejemplos en formato de tablas Markdown:

**1. Nodos**

| Tipo de Nodo | Ejemplo de Código | Descripción |
| --- | --- | --- |
| Nodo de elemento | `<div id="mi-div">Hola mundo!</div>` | El nodo de elemento div con ID mi-div tiene un nodo de texto como hijo. |
| Nodo de atributo | `<img src="imagen.jpg" alt="Mi imagen">` | El nodo de atributo src del elemento img tiene el valor imagen.jpg. |
| Nodo de texto | `<p>Este es un párrafo con <strong>texto en negrita</strong>.</p>` | El nodo de texto dentro del elemento p contiene el texto "Este es un párrafo con". |
| Nodo de comentario | `<!-- Esto es un comentario -->` | El nodo de comentario no se muestra en la página web. |
| Nodo de procesamiento de instrucciones | `<?php echo "Hola mundo!"; ?>` | El nodo de procesamiento de instrucciones se utiliza para ejecutar código PHP. |

**2. Métodos de selección de elementos**

| Método | Ejemplo de Código | Descripción |
| --- | --- | --- |
| getElementById() | `const div = document.getElementById("mi-div"); console.log(div.textContent);` | Selecciona el elemento con el ID especificado. |
| getElementsByClassName() | `const imagenes = document.getElementsByClassName("imagen"); for (const imagen of imagenes) { console.log(imagen.src); }` | Selecciona todos los elementos con la clase especificada. |
| querySelector() | `const parrafo = document.querySelector("p strong"); console.log(parrafo.textContent);` | Selecciona el primer elemento que coincide con el selector CSS especificado. |

**3. Modificación de contenido**

| Método | Ejemplo de Código | Descripción |
| --- | --- | --- |
| textContent | `const div = document.getElementById("mi-div"); div.textContent = "Adiós mundo!";` | Cambia el contenido de texto del elemento seleccionado. |
| innerHTML | `const div = document.getElementById("mi-div"); div.innerHTML = "<p>Hola mundo!</p>";` | Cambia el contenido HTML del elemento seleccionado. |

**4. Eventos**

| Evento | Ejemplo de Código | Descripción |
| --- | --- | --- |
| addEventListener() | `const boton = document.getElementById("mi-boton"); boton.addEventListener("click", () => { alert("¡Hola!"); });` | Añade un evento al elemento seleccionado. |
| click | `<button id="mi-boton" onclick="alert('¡Hola!');">Click aquí</button>` | Añade un evento de clic al elemento seleccionado. |
| mouseover | `<div id="mi-div" onmouseover="this.style.color = 'red';">Hola mundo!</div>` | Añade un evento de pasar el ratón sobre el elemento seleccionado. |

**5. CSS**

| Propiedad | Ejemplo de Código | Descripción |
| --- | --- | --- |
| style | `const div = document.getElementById("mi-div"); div.style.color = "red";` | Cambia el estilo del elemento seleccionado. |
| color | `<div style="color: red;">Hola mundo!</div>` | Cambia el color del texto del elemento seleccionado. |
| size | `<div style="font-size: 20px;">Hola mundo!</div>` | Cambia el tamaño del texto del elemento seleccionado. |
| position | `<div style="position: absolute; top: 10px; left: 10px;">Hola mundo!</div>` | Cambia la posición del elemento seleccionado. |
