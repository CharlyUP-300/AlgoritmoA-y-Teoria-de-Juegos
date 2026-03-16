# Algoritmo A*

es un algoritmo de búsqueda de caminos y recorrido de grafos que se utiliza para encontrar el camino más corto entre un punto inicial y un objetivo.

### Su Funcion
El proceso es el siguiente:
1.	Se empieza desde el nodo inicial.
2.	Se calculan los valores f(n) para los nodos vecinos.
3.	Se selecciona el nodo con menor costo estimado.
4.	Se repite el proceso explorando nuevos nodos.
5.	Cuando se llega al nodo objetivo, se obtiene el camino más corto.
Este proceso permite encontrar soluciones óptimas y eficientes.

### Su Uso
Se usa mucho en:
•	Inteligencia Artificial
•	Videojuegos (movimiento de personajes)
•	Sistemas de navegación y GPS
•	Robótica

La idea principal del algoritmo es explorar primero las rutas que parecen más prometedoras, para encontrar la solución más rápida y eficiente.

### Fórmula:

f(n) = g(n) + h(n)

donde:
g(n) = costo desde el inicio
h(n) = heurística o estimación al objetivo



---

# Heurística

Una heurística es una técnica o estrategia que ayuda a resolver problemas más rápido usando estimaciones o reglas prácticas en lugar de analizar todas las posibilidades.

se utilizan para hacer más eficiente la búsqueda de soluciones, especialmente cuando un problema tiene demasiadas posibilidades.

Sirven para:
- Reducir el número de caminos que el algoritmo analiza
- Encontrar soluciones más rápido
- Guiar algoritmos de búsqueda como A*
- Resolver problemas complejos de inteligencia artificial

### ¿Cómo funciona?

La heurística calcula una estimación del costo restante:

h(n)

Esta estimación se suma al costo recorrido para calcular el valor total del nodo.

---

# Teoría de Juegos

La teoría de juegos es una rama de las matemáticas y la economía que estudia situaciones donde varias personas (o jugadores) toman decisiones y el resultado depende de lo que hagan los demás. 

La teoría de juegos se utiliza para analizar decisiones estratégicas en muchos campos. La idea principal es predecir qué decisiones tomarán los jugadores cuando cada uno intenta obtener el mejor resultado.

Elementos:

- Jugadores
- Estrategias
- Resultados

---

# Ejemplos en Python

En el Colab se implementaron ejemplos de cada uno de los conceptos vistos anteriormente.

---

# Autor: Charly Jhoan Murillo Hernandez (12200263)

Estudiante de Ingeniería de Sistemas
