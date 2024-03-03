#  Estilos Globales 
1 Elimina el margen predeterminado, asegurando que no haya espacio adicional alrededor del borde de la página 

2 Establece la fuente principal del texto en el cuerpo del documento. Si 'Arial' no está disponible, utiliza una fuente sans-serif de respaldo. 

`` body {
    margin: 0;
    font-family: 'Arial', sans-serif;} ``

## Estilos para el Encabezado (header)

1  Establece el color de fondo del encabezado en un tono de gris oscuro
2  Añade un relleno de 15 píxeles en la parte superior e inferior del encabezado 

``header {
    background-color: #333;
    padding: 15px 0;}``

## Estilos para la Navegación (nav) 

 1 Elimina los estilos de lista predeterminados: sin viñetas y sin sangría

 2 Elimina el margen predeterminado

3 Elimina el relleno predeterminado 

4 Centra el texto dentro de la lista horizontalmente

``nav ul {
    list-style: none;
    margin: 0; 
    padding: 0; 
    text-align: center;
}``

1 Establece la visualización de los elementos de lista como en línea 

2 Agrega un margen a la derecha de cada elemento de lista para espaciado 

``nav li {
 display: inline;
margin-right: 20px;
}``

1 Elimina el subrayado del enlace

2 Establece el color del texto en blanco

3 Establece el peso de la fuente en negrita 

4 Establece el tamaño de la fuente en 16 píxeles 

5 Agrega una transición suave al color del texto durante 0.3 segundos

``nav a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 16px;
    transition: color 0.3s ease;
}``

1 Cambia el color del texto al azul claro cuando el enlace se encuentra en estado de "hover" (sobre) 

``nav a:hover {
    color: #66ccff;
}
``