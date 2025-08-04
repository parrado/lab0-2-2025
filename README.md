<h1 align="center">
Lab 0: Lógica de Programación (RA 1, RA 3 y RA 4) <br />
 </h1>
 <p align="center">
Alexander López-Parrado, PhD. <br />
Programación, II-2025 <br />
GDSPROC <br />
Uniquindío <br />
</p>

Esta práctica de laboratorio busca retomar aquellos conocimientos y habilidades adquiridos en el espacio académico Lógica de Programación. Para tal fin, se pondrá en práctica aspectos relacionados con la lógica para la creación de programas de computadora y su implementación en el lenguaje de programación Python.

En ese sentido, la práctica de laboratorio contempla el repaso de estructuras de programación tales como: declaración de variables, sentencias condicionales, sentencias para ciclos, arreglos y funciones. 

## Sentencias Condicionales

En esta sección repasará y pondrá en práctica de nuevo las sentencias condicionales del lenguaje de programación Python. Para lo anterior, considere el programa en el archivo [bsa.py](bsa.py) que estima el área de la superficie corporal (*Body Surface Area*) a partir del peso y estatura de una persona [[1]](#1).

1.	Ejecute el programa con distintos valores de altura y peso, tome nota de los resultados de BSA.
2.	Cree un nuevo programa (```bsa_cat.py```) a partir de [bsa.py](bsa.py) que solicite al usuario altura y peso, calcule la superficie corporal con la función  (```bsa```), y luego clasifique esa BSA según rangos clínicos reales que pueden consultar mediante una herramienta de IA (Inteligencia Artificial) generativa (ChatGPT, DeepSeek, Gemini). No usar la herramienta IA para la generación del código.
3.	Ahora use la herramienta IA para generar el código del punto anterior, verifique el correcto funcionamiento del programa generado y compare con la implementación realizada por usted.


## Ciclos y Arreglos

En esta sección se considerarán las sentencias para ciclos y el uso de arreglos en el lenguaje de programación Python. Para esto, considere los programas de la sección anterior.

1.	Cree un programa a partir de(```bsa_cat.py```) que solicite al usuario un número de personas y que posteriormente solicite la altura y el peso para cada una de ellas, calcule la superficie corporal individual y almacene la categoría correspondiente, al finalizar, imprima la lista completa de categorías obtenidas.
2.	Modifique el programa del punto anterior para que se calcule e imprima el porcentaje de personas que se encuentran en cada una de las categorías (“Bajo”, “Normal” o “Alto”).
3.	Ahora use la herramienta IA para generar el código del punto anterior, verifique el correcto funcionamiento del programa generado y compare con la implementación realizada por usted.





## Funciones

Para terminar, en esta sección pondrá en práctica la creación de funciones en el lenguaje de programación Python. Recuerde que las funciones son construcciones que permiten crear código modular, escalable y de mayor legibilidad. Para lo anterior, considere el programa que construyó en el punto 2 de la sección [Sentencias Condicionales](#sentencias-condicionales).

1. Realice una modificación al programa para que se le informe al usuario el rango de peso para que su BSA sea considerada normal. Para lo anterior, cree una función que realice el cálculo del peso para lograr una BSA normal de acuerdo a la estatura del usuario.


## Entrega del laboratorio

El laboratorio debe ser presentado mediante:

1. Repositorio en GitHub.
2. Informe de laboratorio.

El informe de laboratorio y el enlace al repositorio de GitHub deben ser compartidos en el enlace dispuesto para tal fin en la plataforma Google Classroom.

## Referencias

<a id="1">[1]</a> 
Calculator.net, "Body Surface Area Calculator",url=https://www.calculator.net/body-surface-area-calculator.html.
