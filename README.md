# juego-de-la-vida
juego de la vida william
Simulaciones y Juego de la Vida en Python

Este proyecto contiene una colección de simulaciones basadas en modelos computacionales, incluyendo el Juego de la Vida (en una y dos dimensiones), simulaciones epidemiológicas (COVID-19) y generadores de distribuciones aleatorias.

El objetivo es explorar el comportamiento de sistemas dinámicos, la evolución de poblaciones y la generación de datos estocásticos.

Estructura del Proyecto
Archivo	Descripción
game_of_life_1d.py	Implementa el Juego de la Vida unidimensional, mostrando la evolución de celdas vivas y muertas a través del tiempo.
game_of_life_2d.py	Implementa el Juego de la Vida bidimensional basado en las reglas de Conway, con visualización matricial.
covid_simulation.py	Simula la propagación del COVID-19 considerando contagios, recuperaciones y muertes bajo condiciones ajustables.
random_generators.py	Generadores de números aleatorios usados por los distintos modelos.
distribuciones_app.py	Interfaz o módulo que permite probar distribuciones de probabilidad.
simulaciones_app.py	Punto de entrada general que integra las distintas simulaciones.
 Ejecución



Ejecuta la aplicación principal:

python simulaciones_app.py


Desde el menú podrás seleccionar:

Juego de la Vida 1D o 2D

Simulación de COVID-19

Pruebas de distribuciones o generadores aleatorios

Requisitos

Python 3.8 o superior

Librerías estándar (math, random, time)

Opcional: matplotlib para visualizaciones

Instálala (si se usa):

pip install matplotlib

🧩 Modelos Implementados
🔹 Juego de la Vida

Basado en las reglas de Conway:

Celdas vivas con 2 o 3 vecinos permanecen vivas.

Celdas muertas con exactamente 3 vecinos reviven.

Las demás celdas mueren o permanecen muertas.

Incluye versiones:

1D → Representación lineal del autómata celular.

2D → Representación matricial con visualización por consola o gráfico.

Simulación de COVID-19

Modelo basado en agentes con estados:

S (Susceptible)

I (Infectado)

R (Recuperado)

D (Fallecido)

Permite observar la evolución de la epidemia a lo largo de los días.

Distribuciones y Generadores

Incluye funciones para:

Generación de números pseudoaleatorios

Pruebas de uniformidad

Distribuciones básicas (normal, binomial, etc.)

Autor

Proyecto desarrollado por Kevin William Fernández Madriaga
Año: 2025
Proyecto académico sobre Simulación y Modelos Computacionales.
