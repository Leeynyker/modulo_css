# Medidas
## Medidas absolutas
El tamaño se expresa en la unidad de medida sin hacer referencia a otro elemento.

| Medida | Nombre    |Equivalencia |
|------  |-----------|-------------|
|cm      |Centimetro |             |
|mm      |Milimetro  |             |
|in      |Pulgada    |96px ó 2.54cm|
|px      |Pixel      |1/96 in      |
|pt      |Punto      |1/72 in      |
|pc      |Pica       |12pt         |

Las  medidas absolutas se usan cuando el tamaño necesita ser el mismo sin importar el tipo de dispositivo o el tamaño de la pantalla.

De las medidas absolutas la mas usada es el pixel, suele usarse para el tamaño de los contenedores, bordes y tamaño de letra (aunque para este ultimo caso es recomendable usar medidas relativas)



## Medidas relativas
El tamaño es relativo a otro elemento (Contenedor principal, elemento raíz, ancho/alto del viewport, etc.)

| Medida | Relativo                                       |
|--------|------------------------------------------------|
|%       |Relativo al elemento padre                      |
|em      |Relativo al tamaño de la letra del elemento     |
|rem     |Relativo al tamaño de la letra del elemento raiz|
|fr      |Una fracción del espacio disponible en CSS grid |
|ex      |Relativo al alto de "x"                         |
|ch      |Relativo al ancjo del "0"                       |
|vw      |% del ancho de la pantalla                      |
|vh      |% del alto de la pantalla                       |
|vmin    |% del minimo entre vw y vh                      |
|vmax    |% del maximo entre vw y vh                      |

Estas medidas se usan para que los tamaños se ajusten segun el tamaño de los contendores o los dispositivos, actualmente el contenido virtual se consume desde distintos terminales (Computadores, tablets,celulares, televisores, entre otros) por lo que usar medidas  relativas nos permite mantener la estetica de nuestro sitio web en los diferentes tamaño de pantalla y además brindar una mejor experiencia al usuario.

***
| Anterior                   | Siguiente                     |
|----------------------------|-------------------------------|
| [Herencia](/herencia/) | [Variables](/variabls/)|