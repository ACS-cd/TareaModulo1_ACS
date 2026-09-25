ÍNDICE

[**Parte 1	2**](#parte-1)

[Conceptos básicos	2](#conceptos-básicos)

[Clasificación de lenguajes de programación	3](#clasificación-de-lenguajes-de-programación)

[**Parte 2	4**](#parte-2)

# **Parte 1** {#parte-1}

## *Conceptos básicos* {#conceptos-básicos}

*Código fuente*

Conjunto de instrucciones realizadas en lenguaje de programación que marca el comportamiento de un programa o aplicación. Necesita ser traducido al lenguaje máquina para que un ordenador pueda ejecutarlo.

*Código objeto*

Es el código fuente traducido (o compilado) por un programa compilador, el cual transforma las instrucciones en algo más cercano a lo que la máquina entiende pero no es ejecutable.

*Código ejecutable*

Es la versión final del código que el ordenador puede ejecutar directamente. Contiene todas las instrucciones en lenguaje máquina (binario).

*Fases de programación*

1. Definir el problema. Aquí se analiza el problema de la situación inicial y hacia dónde se quiere llegar con el programa.  
2. Analizar el problema. Recopilar los datos necesarios y qué se quiere producir al final.  
3. Diseño del algoritmo. Creación del código en lenguaje de programador.  
4. Compilación (Pasamos de código fuente a código objeto)

            *Fases de la compilación*  
               *Análisis léxico. Lee y clasifica el contenido del código fuente.*  
               *Análisis Sintáctico. Comprueba el orden de los elementos.*  
   *Análisis Semántico. Verifica si las frases tienen sentido.*

5. Prueba y depuración de errores. Comprobación del código, arreglo de bugs y campo de pruebas.  
6. Mantenimiento. Fase final, donde se implementan actualizaciones para alargar la vida del programa.

## *Clasificación de lenguajes de programación* {#clasificación-de-lenguajes-de-programación}

|  | Nivel de abstracción | Paradigma de programación |
| :---- | :---- | :---- |
| Ensamblador | Bajo nivel | Imperativo |
| Lenguaje máquina | Bajo nivel | Imperativo |
| Python | Alto nivel | Declarativo |
| SQL | Alto nivel | Declarativo |
| Swift | Medio nivel | Híbrido |
| Fortran | Medio nivel | Imperativo |

¿Por qué pertenecen a cada clasificación?

Ensamblador: Se denomina lenguaje de bajo nivel por ser cercano al lenguaje máquina e imperativo por señalar cada paso punto por punto y en el orden que el ordenador lo ejecuta.  
Lenguaje máquina: De bajo nivel por estar escrito en código binario, un lenguaje incomprensible para el ser humano. Clasificado como imperativo por determinar las instrucciones ordenadas que la máquina debe ejecutar, sin orden la máquina no ejecuta.  
Python: Se caracteriza como un lenguaje de alto nivel por su sintaxis clara y fácil de leer. Si bien el programa se puede etiquetar como declarativo por su escritura de instrucciones ordenadas, Python puede permitir otros tipos de paradigmas en situaciones concretas.  
SQL: Es un lenguaje de alto nivel por priorizar la legibilidad del programa y un fácil uso del mismo. Con este lenguaje podemos escribir lo que queremos en vez de las instrucciones y el programa es capaz de llegar a dicha solución.  
Swift: Se etiqueta como lenguaje de medio nivel por su control de memoria y eficiencia de sistemas. Este lenguaje se denomina híbrido, una categoría para lenguajes donde es posible diversidad de formas para explicar instrucciones a una máquina.  
Fortran: Medio nivel. Trabaja con algunas abstracciones como también lenguaje cotidiano, permite un mayor entendimiento que los lenguajes de alto nivel para el ojo humano. Denominado imperativo porque el código describe las instrucciones paso a paso de forma secuencial empleando estructuras fijas.

# **Parte 2** {#parte-2}

## *Identificación de paradigmas de programación:*

A continuación, se te ofrecen descripciones de fragmentos de código. Tu tarea es identificar si cada uno corresponde a un paradigma imperativo o declarativo y justificar tu respuesta.

* **Fragmento 1 (Descripción):**

Un programa recorre una lista de números sumándolos uno por uno hasta obtener el total. Pista: Se describe cómo se realiza la suma paso a paso.

Imperativo.

* **Fragmento 2 (Descripción):**

Una consulta a una base de datos busca empleados mayores de 30 años y devuelve solo sus nombres. Pista: Se especifica qué resultado se quiere obtener sin detallar cómo se procesa internamente.

Declarativo.

* **Fragmento 3 (Descripción):**

Un programa que calcula el factorial de un número n definiendo que el factorial de 0 es 1 y, para números mayores, multiplicando el número por el factorial del número anterior. Pista: La lógica se define recursivamente sin especificar los pasos detallados.

Declarativo

* Fragmento 4 (Descripción):

Un programa filtra productos con precios superiores a 10 dólares recorriendo una lista y comprobando cada producto uno por uno. Pista: Se describen detalladamente los pasos del proceso.

Imperativo.

## Actividad en grupo:

En equipos de 2-3 personas, seleccionen una actividad cotidiana (preparar una receta, organizar un evento, etc.) y describan la tarea de dos maneras:

* Imperativa: Indicando cada uno de los pasos detallados.  
* Declarativa: Describiendo únicamente el resultado final que quieren lograr.

  Comparen las dos descripciones y discutan las ventajas y desventajas de cada enfoque. Incluyan esta comparación en el informe.

