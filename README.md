# 10  REGLAS DE ORO DE FLEXBOX

Flexbox es una nueva forma de diseñar nuestros sitios web. Está conformado por un conjunto de propiedad de CSS pensadas en crear interfaces web.

Nos permite ahorrar la escritura de muchas líneas de código CSS y obtener un mayor control del posicionamiento y comportamiento del los bloques que conforman el diseño de nuestras páginas web.

EL siguiente repositorio tiene como objetivo monstrar un resumen de lo aprendido en el siguiente curso:

https://www.udemy.com/curso-de-flexbox-desde-0/



## REGLA #1

Flexbox necesita un padre y por lo menos un hijo

![](https://i.imgur.com/wlbLO5t.png)


La altura depende del padre y su ancho de la etiqueta depende de la cantidad del contenido que tenga.

## REGLA #2
El flex conteiner(contenedor Padre) tiene 2 ejes

![](https://i.imgur.com/1JMcubE.png)


Eje principal(horizontal) y secundario(vertical), indican la manera como se van a mover dentro del flex container.

![](https://i.imgur.com/LTEULQs.png)


## REGLA #3

Podemos modificar el eje principal con la propiedad: flex-direction

![](https://i.imgur.com/LHtD6q1.png)

## REGLA #4

Podemos permitir el salto de columnas con flex-wrap

![](https://i.imgur.com/QqDh13s.png)

Cuando los hijos ya no tengan espacio en donde caber en el padre flexbox les obliga a que a que se queden en una unica linea pero con flex-wrap le obligamos a saltar de linea.

## REGLA #5

Alineamos elementos en el eje principal con justify-content

![](https://i.imgur.com/ON1bV78.png)

## REGLA #6

Alineamos elementos en el eje secundario con align-items

![](https://i.imgur.com/ym3lhad.png)

## REGLA #7

Podemos alinear los elementos hijos de forma individual en el eje secundario con align-self

![](https://i.imgur.com/Q9PyPPP.png)


## REGLA #8

Los hijos flexibles ignoran propiedades como float,clear,vertical-align pero para el padre si.


## REGLA #9

Podemos modificar el tamaño de los hijos con flex-grow,flex-shrink,flex-basis

![](https://i.imgur.com/Vk5ceB4.png)

## REGLA #10

Podemos resumir todo con la propiedad: flex

![](https://i.imgur.com/LG59sHD.png)

Flex permite agrupar las propiedades en una única flex-grow | flex-shrink | flex-basis
flex: flex-grow flex-shrink flex-basis
flex: flex-grow flex-basis
