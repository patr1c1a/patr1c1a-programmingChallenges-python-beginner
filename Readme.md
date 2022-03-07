# ESPAÑOL
*[(scroll down or click here for English version)](#english)*

## Objetivo

Este proyecto intenta ser una herramienta con la cual practicar desafíos (o ejercicios) de programación, desde un nivel
inicial, usando Python 3.

Los ejercicios se enfocan en desarrollar habilidades algorítmicas y de razonamiento lógico así como aprender a trabajar
con las bases de la programación y los tipos de datos fundamentales. No se centra en aprender los detalles del lenguaje
Python. Es por ello que se alienta a que desarrolles tus propias soluciones en lugar de utilizar algunas herramientas
que provee el lenguaje.

Los desafíos se dividen en temas para ayudarte a practicar ciertos tipos y estructuras de datos, pero eso no excluye
otras posibles soluciones (que podrían incluso ser más eficientes).

## Cómo está planteado el proyecto

Se presenta una serie de funciones incompletas (sin su cuerpo), y cierta documentación que muestra cómo debería
comportarse cada función. Además, cada función tiene una serie de pruebas (tests) unitarias. Necesitarás completar el
cuerpo de las funciones de acuerdo a la consigna de cada una, de manera que todas las pruebas pasen.

Al ejecutar el proyecto, se correrán las pruebas para evaluar si el resultado es el esperado.

Los ejercicios están divididos en las siguientes categorías o temas: *números, strings, listas y tuplas, conjuntos* y
*diccionarios*; lo que significa que se sugiere resolverlos utilizando estos tipos de datos con el fin de practicar las
bases. Pero también pueden resolverse en otras formas, siempre que los tests pasen exitosamente.


## Cómo usar este proyecto

Python 3 deberá estar instalado en el sistema.

Asumiendo que usarás la versión en español, primero ingresa en la carpeta **ESP**. Ésta contiene dos carpetas: **src** y
**tests**. La carpeta **src** contiene archivos relacionados a cada tema (de los mencionados arriba) y en cada archivo 
se encuentran varias funciones con el cuerpo vacío, que deberás completar con tu código. La carpeta **tests** incluye 
las pruebas unitarias y su contenido no debe ser modificado.

Para probar tu código, corre el archivo **ejecutar_tests.py**, el cual mostrará el resultado en consola. Es posible usar
un IDE para ejecutarlo o bien hacerlo desde línea de comandos. Para esto último, primero cambia al directorio ("CD") a 
la carpeta ESP del proyecto y luego corre ejecutar_tests.py usando Python (deberás usar un comando como 
`python run_tests.py` o `python3 run_tests.py`).

Inicialmente, todas las pruebas fallarán. El objetivo es escribir el cuerpo de las funciones (reemplazando la
instrucción "pass" por tu código) para hacer que las pruebas pasen: esto se indica con el resultado "ok".

Es posible obviar la ejecución de alguna categoría de tests, comentando (con un # delante) la línea correspondiente en 
el archivo **ejecutar_tests.py**. La línea a comentar se verá como esta: 
`suite.addTests(loader.loadTestsFromModule(tests.archivo_a_obviar))`.


### Cómo escribir el código

Completar el cuerpo de cada función de manera que cumpla con lo que se espera de ella, según la documentación (no
olvides eliminar la instrucción "pass"). Esta documentación indica el objetivo de la función, qué representan y de qué
tipo son los parámetros y qué se espera que retorne.

Solo se debe agregar contenido a las funciones, sin modificar nada más (nombre, parámetros o documentación de las
funciones) ni el resto del archivo, ni las pruebas unitarias.


### Orden de los temas

Aunque es posible comenzar por cualquiera de los temas propuestos, existe un orden que permite resolverlos con
dificultad incremental:

1. Números
2. Strings
3. Listas y tuplas
4. Conjuntos y diccionarios

Esto implica que los ejercicios del módulo numeros.py pueden resolverse sin utilizar strings, listas, conjuntos ni
diccionarios. Los ejercicios del módulo strings pueden incluir manipulación de números. Los ejercicios de listas y
tuplas pueden incluir manipulación de números y de strings. Los ejercicios de conjuntos pueden incluir listas, strings
y números. Finalmente, los ejercicios de diccionarios pueden incluir cualquiera de los temas anteriores (conjuntos,
listas, tuplas, strings y números).


### Abordaje sugerido

Al escribir código con fines profesionales es más probable que muchas de las tareas incluidas en estos ejercicios se
resuelvan mediante herramientas predefinidas del lenguaje. Pero se recomienda que en este proyecto intentes evitar
usarlas y crees tus propios algoritmos, a fin de ejercitar el razonamiento lógico y las estructuras básicas de la
programación. Con esa intención, en algunas funciones se sugiere evitar ciertas herramientas y encontrar soluciones
alternativas.

Todos los desafíos planteados en este proyecto pueden ser resueltos sin necesidad de importar bibliotecas o módulos
adicionales (solo modificando el cuerpo de cada función).

Además, las categorías planteadas sugieren ciertos tipos y estructuras de datos para ayudar a reforzar el pensamiento
algorítmico, incluso cuando podrían encontrarse soluciones alternativas más eficientes. De todas formas, nada impide que
resuelvas los ejercicios de la forma en que te parezca mejor, ya que estos temas son solo una sugerencia para guiar la 
práctica.

También pueden utilizarse los casos de prueba para resolver los desafíos mediante "desarrollo guiado por pruebas" (en
inglés, "Test-Driven-Development" o "TDD"), de manera que las pruebas guíen el desarrollo de los algoritmos.

---
# ENGLISH

## Goal

This is a project you can use to practise programming challenges (or exercises) for beginners, using Python 3.

Exercises are mainly intended to help develop algorithmic and logical reasoning skills as well as learn how to work with
programming fundamentals. It doesn't focus on learning the perks of the Python language. That's why in most cases you're
encouraged to build your own solution instead of using some pre-made solutions that Python offers.

Challenges are divided into topics to help you practise with specific data types and structures, but that doesn't mean 
there can't be other possible solutions (that might even be more efficient).

### How the project is organized

The project includes a variety of functions where their body is missing, and some documentation showing how each
function should behave. Also, each function has a set of unit tests. You'll need to fill in the blanks (that is: write
the function body) without modifying anything else, to get all tests to pass.

When the project is executed, tests are run to evaluate if the functions return the expected result in each case.

Exercises are divided into topics: *numbers, strings, lists and tuples, sets* and *dictionaries*; meaning you're 
encouraged to solve challenges using these data types in order to practise programming fundamentals. But they can be
solved in other ways too, as long as the tests pass successfully.


## How to use the project

Python 3 needs to be installed.

Assuming you'll be using the English version of the project, first go into the **ENG** folder. In there, there are two 
folders: **src** and **tests**. The **src** folder contains files related to a specific topic (from the topics mentioned 
above), with functions with a blank body (this is where you'll add your code). The **tests** folder contains unit tests 
and should not be modified at all.

To test your code, execute the **run_tests.py** file, which will output the results to the console. You can use an IDE 
to run the code or just run it from command line. To do the latter, first change directory to the project's ENG folder 
and then execute run_tests.py using Python (you might need to use a command like `python run_tests.py` or 
`python3 run_tests.py`). 

At first, all tests are expected to fail. The goal is to fill in the function bodies (replacing the "pass" statement) 
to get the tests to pass (they will show an "ok" result), one by one.

You can skip a test category from executing by commenting out (using a leading #) the related line in the 
**run_tests.py** file. The line that needs to be commented will look like this: 
`suite.addTests(loader.loadTestsFromModule(tests.file_to_skip))`.


### How to write the code

Fill in the body of each function in a way that makes it behave as the documentation states (remember to remove the 
"pass" statement and add your code instead). Documentation is included between triple quotes (""") and designates what 
the function goal is, what's the data type of each parameter and what they represent, and what's the expected return 
value.

Only function body needs to be added, without modifying anything else (name, parameters, documentation, etc.) in the 
function, the overall file or the unit tests.


### Topic order

It's possible to start with any of the included topics (files), but there's a preferred order that allows to solve 
challenges with increasing difficulty:

1. Numbers
2. Strings
3. Lists and tuples
4. Sets and dictionaries

This means that exercises in the numbers.py module can be solved without using strings, lists, tuples, sets or 
dictionaries. But the challenges in strings.py module may include number as well as string manipulation. Challenges in 
the list and tuples module can include number and string manipulation. Then challenges with sets can include working 
with lists, tuples, strings and numbers. Finally, the dictionary challenges can include any of the previous types 
(numbers, strings, lists, tuples and sets).  


### Recommended approach

When writing professional code most likely many of the tasks in these challenges are solved by just using built-in 
tools. But the recommended approach here is to avoid using them and writing our own algorithms instead, to exercise 
logical reasoning and programming fundamentals. This is why some functions suggest avoiding some specific tools.

All the challenges in the project can be solved without the need of importing any libraries (so only the function bodies
should be modified).

Also, the challenge topics suggest specific data types and structures to help improve algorithmic thinking, even when 
there might be more efficient solutions. Feel free to solve the problems in any way you think best, as this is only a 
suggestion.

In addition, test cases can be used to solve the challenges in a Test-Driven-Development ("TDD") fashion, by using unit 
tests to guide development.
