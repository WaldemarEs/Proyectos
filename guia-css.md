# Mi guia de uso practico de Css

El CSS (Cascading Style Sheets) Son __Hojas de estilos en cascada__ y se utilizan para el diseño, formato y apariencia visual de las paginas webs.

### Selectores

Para definir el css o estilos del documento `html` usaremos los __selectores__

En donde `p` selecciona todos los elementos de tipo `p` del documento `HTML` para luego hacer la declaración de estidos del elemento, `p { color: red};`. Por otro lado podemos usar selectores multiples para hacer declaracion de estilos a varios elementos a la vez, separandolos con una coma. `h1, p {color, red};` 

### Clases y selectores ID

 En CSS, una __clase__ es un identificador que comienza con un punto `.` seguido por un nombre único. Esta nomenclatura permite aplicar estilos a uno o más elementos `HTML` que tienen asignada esa clase en su atributo class. Por ejemplo `.mi-clase { color: red};`
 En este caso `.mi-clase` es un __Selector de clase__ y se puede agregar esta clase a cualquier elemento de `HTML` de la siguiente manera `<section class="mi-clase">`.
 Una clase proporciona una forma eficiente de aplicar estilos consistentes a varios elementos en tu página web, facilitando la organización y el mantenimiento del código CSS.

 Los selectores de __ID__ en CSS están basados en elementos del atributo __ID__ de `HTML`. Para seleccionar un elemento por su __ID__, se utiliza el símbolo `#` seguido del valor del __ID__. Un ejemplo seria `#mi-id{ color: red};`. En este caso, `#mi-id` es un selector de __ID__ que se puede utilizar para aplicar estilos a un elemento `HTML` que tenga el atributo id con el valor `mi-id` para asignarlo a un elemento `HTML` solo debemos agregarlo `<div id="mi-id">`.

