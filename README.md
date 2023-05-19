[Repositorio en proceso]

Biblioteca de Juegos y Algoritmos de Aprendizaje. En el nos encontramos 3 secciones principales. 

   1) **Desarrollo de videojuegos.** Creación de videojuegos para uso común del usuario.
   2) **Algoritmos de resolución sencillos.** En esta sección desarrollaremos algoritmos sencillos para resolver y pasarnos los juegos, como busqueda binaria, tree search y sistemas expertos (distinción de casos).
   3) **Algoritmos de aprendizaje automático.** En esta sección aplicaremos técnicas más avanzadas, aunque no por ello son siempre la mejor opción, como: machine learning, deep learning y algoritmos genéticos.

# Índice
 
 1. [Desarrollo de videojuegos](#id1)
    - [Snake](#id1.1)
    - [Tres en raya](#id1.2)
    - [Sudoku](#id1.3)
    - [Flappy Bird](#id1.4)
    - [Ajedrez](#id1.5)
    - [Laberinto](#id1.6)
    - [Arkanoid](#id1.7)

 2. [Algoritmos de resolución sencillos](#id2)
    - [Sudoku](#id2.1)
    - [Búsqueda del camino más corto](#id2.2)

 3. [Algoritmos de aprendizaje automático](#id3)
    - [Algoritmo Genético - Flappy Bird](#id3.1)
    - [Introducción a diferentes modelos de IA - Tres en raya](#id3.2)





# Desarrollo de videojuegos <a name=id1> </a>

|              Preview             |     Link     |
|--------------------------------------------------------------------|--------------| 
<a name=id1.1> </a>
| <image src="/images/snake.gif" width="250" height="250">    |  </p> <p align="center"> [Snake](https://github.com/JavierAM01/Juego-Snake) </p> | 
<a name=id1.2> </a>
| <image src="/images/3enraya.gif" width="250" height="250">  |  </p> <p align="center"> [Tres en raya](https://github.com/JavierAM01/Juego-3enRaya) </p> |
<a name=id1.3> </a>
| <image src="/images/sudoku.gif" width="250" height="250">   |  </p> <p align="center"> [Sudoku](https://github.com/JavierAM01/Juego-Sudoku) </p> |
<a name=id1.4> </a>
| <p align="center"><image src="/images/flappybird.gif" height="250"></p>| </p> <p align="center"> [Flappy Bird](https://github.com/JavierAM01/Juego-FlappyBird) </p> |
<a name=id1.5> </a>
| <image src="/images/ajedrez.gif" width="250" height="250">  |  </p> <p align="center"> [Ajedrez](https://github.com/JavierAM01/Juego-Ajedrez) </p> |
<a name=id1.6> </a>
| <image src="/images/laberinto.gif" width="250" height="250">|  </p> <p align="center"> [Laberinto](https://github.com/JavierAM01/Juego-Laberinto) </p> |
<a name=id1.7> </a>
| <image src="/images/arkanoid.gif" width="250" height="250"> |  </p> <p align="center"> [Arkanoid](https://github.com/JavierAM01/Juego-Arkanoid) </p> |

</p> <p align="center">  </p>


# Algoritmos de resolución sencillos <a name=id2> </a>

## Sudoku <a name=id2.1> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <image src="/images/sudoku.gif" width="250" height="250"> | El algoritmo de resolución de Sudoku utiliza la recursividad para resolver este desafiante rompecabezas. La idea principal es descomponer el problema en subproblemas más pequeños y resolverlos de forma recursiva. El algoritmo busca una casilla vacía en el tablero y prueba diferentes números del 1 al 9 para colocar en esa casilla, verificando si cumple con las reglas del Sudoku. Si se encuentra una solución válida, se avanza a la siguiente casilla vacía y se repite el proceso. Si no se encuentra una solución válida, se retrocede y se prueba con otro número. Este proceso continúa hasta llenar todas las casillas o hasta encontrar una solución completa. La recursividad permite explorar todas las combinaciones posibles de números de manera eficiente. <p align="center"><a href=https://github.com/JavierAM01/Juego-Sudoku> ver código </a></p> |
| <image src="/images/sudoku-2.png" width="250" height="250"> | En este repositorio, presento una versión más humana del algoritmo de resolución de Sudoku. En lugar de depender únicamente de la recursividad, esta versión utiliza diferentes técnicas para encontrar las posibilidades de cada casilla vacía en función de las filas, columnas y bloques en el tablero. Mediante un enfoque meticuloso, se exploran diferentes estrategias para reducir las opciones y tomar decisiones informadas en cada paso. Además, se incorporan métodos más avanzados que permiten identificar patrones y realizar inferencias lógicas. Esta nueva implementación proporciona una experiencia más cercana a la forma en que los humanos abordan y resuelven los Sudokus, lo que brinda una perspectiva interesante sobre las técnicas de resolución del juego. <p>El código está hecho en Haskell, por lo que los gráficos son más primitivos.</p> <p align="center"><a href=https://github.com/JavierAM01/Juego-Sudoku-2> ver código </a></p> |


## Búsqueda del camino más corto <a name=id2.2> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <image src="/images/algo1.gif" width="250" height="250"> | Algoritmo de [Dijkstra](https://es.wikipedia.org/wiki/Algoritmo_de_Dijkstra). El algoritmo de Dijkstra es un algoritmo de búsqueda de caminos más cortos en un grafo ponderado. Se utiliza para encontrar la ruta más corta desde un nodo de origen a todos los demás nodos en un grafo dirigido o no dirigido. Funciona asignando una distancia provisional a cada nodo y actualizando estas distancias a medida que se explora el grafo, siempre seleccionando el nodo con la distancia provisional más pequeña hasta llegar al nodo de destino o a todos los nodos alcanzables desde el nodo de origen. <p align="center"><a href=https://github.com/JavierAM01/Juego-ShortestPath> ver código </a></p>|
| <img src="/images/algo2.gif" width="250" height="250"> | Modificación del algortimo de Dijkstra. A este se le añade el hecho de que el camino más corto entre dos puntos es una línea recta, así acortamos la búsqueda en algunas ocasiones. <p align="center"><a href=https://github.com/JavierAM01/Juego-ShortestPath> ver código </a></p>|
   




# Algoritmos de aprendizaje automático <a name=id3> </a>

## Algoritmo Genético - Flappy Bird <a name=id3.1> </a>

|                  Preview                |    Algorithm     |
|-----------------------------------------|------------------|
| <img src="/images/ai/flappybird.gif" height="300" width="170"> | En este proyecto, exploramos la poderosa aplicación de un algoritmo genético en la resolución del desafiante juego Flappy Bird. Mediante la representación de las aves como individuos en una población y la aplicación de operadores genéticos como selección, cruzamiento y mutación, buscamos encontrar la combinación óptima de características y comportamientos que maximicen la habilidad de evitar obstáculos y obtener puntuaciones altas. A través de la optimización iterativa basada en la evaluación de fitness y la evolución generacional, el algoritmo genético converge hacia soluciones cada vez mejores. Descubre cómo esta técnica matemática nos permite abordar problemas complejos y lograr resultados impresionantes en el contexto del Flappy Bird. <p align="center"><a href=https://github.com/JavierAM01/AlgoritmoGenetico-FlappyBird> ver código </a></p> |

## Introducción a diferentes modelos de IA - Tres en raya <a name=id3.2> </a>

TODO






