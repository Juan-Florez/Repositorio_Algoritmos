Grupo 5

objetivo:
Utilizar algoritmos geneticos para maximizar una función.

Preguntas:

-------------------
1.	Hacer un análisis de complejidad del algoritmo en función de los parámetros dimensionales de configuración(literal a, punto 3 en verde), como también complejidad simplificada O(n).

Complejidad en función de los parámetros de entrada:

-Tamaño genoma: La complejidad es O(n) debido a que en la función listTooDecimal() hay un ciclo for que depende del tamaño del genoma.
-Tamaño población: La complejidad es O(n) debido a que hay ciclos for que dependen de este parámetro, por ejemplo, para medir el éxito de cada individuo de la población.
-Generaciones: La complejidad es O(n) porque la población cambia cada generación, esto se hace en un ciclo for.
-Rango de búsqueda: La complejidad es O(1) porque este parámetro solo determina los valores que pueden tomas los genomas, no afecta el tiempo de ejecución.

--------------------
2.	Cómo reacciona su algoritmo a variadas funciones de optimización (lineal, oscilantes(varias frecuencias), etc)?

Este algoritmo sirve para hallar el máximo global de cualquier tipo de función (lineal, polinómica, exponencial, oscilante, etc). Cuando la función tiene dos puntos máximos (por ejemplo, en la función coseno entre 0 y 2pi) los individuos de cada población se acercan a los dos puntos, sin embargo, al final se imprime solo el punto que se acerque más al máximo. 

------------------------------
3.	Concluya y Describa, por sus experimentos como están relacionados los parámetros de configuración de su algoritmo, con el costo en (tiempo y espacio).

Los parámetros que afectan al tiempo de ejecución son: Tamaño genoma, Tamaño población, generaciones; sin embargo con el que mas se ve afectado el costo en tiempo es generaciones, debido a que en cada generación hay que medir el éxito de sus idividuos, calcular el error, reproducir los mejores individuos y hacer mutaciones.
Los parámetros que afectan al costo de memoria son: Tamaño genoma y Tamaño población, cuando aumenta los valores de estos parámetros hay que crear listas cada vez más grandes.

----------------------------
4.	¿Qué parámetro considera usted más relevante para acelerar la convergencia de la búsqueda?

El parámetro mas importante es el número de generaciones, aunque se cambien los valores de los otros parámetros, si los individuos se reproducen pocas veces, no se va a llegar a una respuesta valida.  
