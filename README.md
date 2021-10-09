# Tranformaciones_2D

Crea un programa donde apliques los cuatro tipos de trnaformaciones 2D usando la libreria de OpenGL

## Escalamiento
Una transformación para alterar el tamaño de un objeto se denomina escalación.
Dependiendo del factor de escalación el objeto sufrirá un cambio en su tamaño pasando a ser mayor, o menor en su segmento de longitud.
Esta es la transformación del objeto especialmente interesante, pues con ella se consigue el efecto Zoom.

![1](https://user-images.githubusercontent.com/71147346/136642733-d776438d-d29b-4bb3-9e46-fdcbc95fcf9a.jpg)

## Rotación
Para rotar un objeto (en este caso bidimensional), se ha de determinar la cantidad de grados en la que ha de rotarse la figura. Para ello, y sin ningún tipo de variación sobre la figura, la cantidad de ángulo ha de ser constante sobre todos los puntos.

Otra forma de conseguir la rotación, respecto a un punto de movimiento, es fijar los diferentes puntos respecto a un punto de fijación siendo los puntos que forman la figura, relativos a este.
La fórmula a aplicar en este último supuesto, sería la siguiente:
X' = X * Cos (àngulo) - Y * Sin(ángulo)
Y' = Y * Cos (ángulo) - X * Sin(ángulo)
 
 ![2](https://user-images.githubusercontent.com/71147346/136642744-2b197856-d3b2-443c-8fe5-202d484ad1f0.jpg)

## Traslación
Es el movimiento en línea recta de un objeto de una posición a otra.
Movimiento de una figura, sin rotarla ni voltearla. "Deslizar".
La figura sigue viéndose exactamente igual, solo que en un lugar diferente.
Se aplica una transformación en un objeto para cambiar su posición a lo largo de la trayectoria de una línea recta de una dirección de coordenadas a otra.

![4](https://user-images.githubusercontent.com/71147346/136642770-ebf73c0a-b97c-4988-9ee8-a2f67476c1f0.jpg)

## Sesgo
Es un tipo de transformación no rígida, pues existe una deformación del objeto original al aplicar dicha transformación. Existen 2 tipos de sesgo:

1. Sesgo Horizontal: las coordenadas adyacentes al eje x permanecen fijas, los valores de y no cambian.
2. Sesgo Vertical: las coordenadas adyacentes al eje y permanecen fijas, los valores de x no cambian.

![3](https://user-images.githubusercontent.com/71147346/136642778-400b7bf0-dede-4515-b692-673d21c50f3e.jpg)

# Resultado

![Captura de pantalla 2021-10-08 223455](https://user-images.githubusercontent.com/71147346/136642874-36e665cc-db9b-4359-b20b-3b375f36807e.jpg)

