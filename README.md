# Algoritmo de Dijkstra

#### Trabajo Práctico realizado para la materia _Algoritmos y Estructuras de Datos_ en la UTN FRBA - Año 2017

Consiste en conocer el camino mínimo (óptimo) que debe hacer un automóvil para ir desde el _Centro de Logística_ hasta el _Centro de Cómputos_ mediante el [algoritmo de Dijkstra](https://es.wikipedia.org/wiki/Algoritmo_de_Dijkstra)

Los nodos son Colegios (C1, C2, etc) y a cada arista le fue asignada un peso (distancia entre colegio y colegio):

![](/grafo.PNG)

También para el cálculo del camino óptimo se tiene en cuenta una demora por tránsito que puede haber entre cada colegio, que se calcula como: (Número Aleatorio entre 0 y 1) x (Velocidad Promedio del Móvil), siendo esta última ingresada al Sistema por el Usuario.

El código se encuentra desarrolado en C++, en el archivo **_dijkstra.cpp_** y el repositorio cuenta con el ejecutable **_dijkstra.exe_** para probar el algoritmo

#### Resultado del Algoritmo:

![](/resultado.PNG)
