***Instrucciones de compilacion***
---
- Insertar los comandos:
- cmake CMakeLists.txt
- make
- ./BusquedaProfundidad

***Consideraciones para graficar OpenGl***
---
- En las lineas 47 - 48 del main.cpp se debe cambiar los valores para que todos los nodos entren en la pantalla.
- La variable "size_Square" es el tamaño de cada cuadrado. Se recomienda disminuirlo para que no opaquen a las lineas
- La variable "scalarWindow" es la que controla todo el tamaño de los nodos y su escala. Para 5 x 5 nodos es bueno poner 10; o para 51 x 51 es bueno poner 60.
- OJO: Para esta varialbe "scalarWindow" SIEMPRE poner un numero mayor a el N x N. (scalarWindow > N). Los parametros de OpenGl van entre 0.0 y 1.0, por lo que se debe asegurar en  transformar dichas posiciones en estos parametros.