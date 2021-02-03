# EDA para la Resolución de Problemas de Optimización con Restricciones

La optimización se refiere al hecho de encontrar el mejor elemento entre un
conjunto de alternativas disponibles, con la intención de minimizar o maximizar
una función objetivo. Las soluciones están compuestas de cadenas de información,
llamadas variables, las cuales pueden estar sujetas a restricciones, de manera que
el propósito principal consiste en encontrar el valor de dichas variables que optimicen la función objetivo.
El proceso de identificar la función objetivo, las variables y las restricciones
de un determinado problema se le conoce como modelado. La construcción del
modelo es el primer paso en el proceso de optimización. Un modelo demasiado
simple puede ser insuficiente para encontrar la solución de problemas complejos,
por otro lado, un modelo demasiado complicado puede llegar a ser más difícil de
resolver que el problema original.

Una vez que el modelo ha sido definido, un algoritmo de optimización puede
ser utilizado para encontrar la solución. Ya que no existe un algoritmo de optimización universal, se han propuesto una gran cantidad de algoritmos capaces de
resolver determinados problemas.
La computación evolutiva ha demostrado ser una herramienta eficiente para
la resolución de diversos problemas de optimización. Existen técnicas que van
desde los algoritmos genéticos (AGs), hasta los algoritmos de estimación de distribución (EDAs); estos últimos representan un área relativamente nueva dentro
de la computación evolutiva, por lo que existe un extenso campo de investigación
respecto a ellos.


Los AGs funcionan en base a la simulación del proceso evolutivo y se componen de tres partes fundamentales: selección, reproducción o cruza y mutación. El
algoritmo consiste en elegir a los mejores individuos de la población, con la intención de que al recombinarse se produzcan mejores soluciones que formen parte de
la siguiente generación; dichas soluciones son susceptibles de sufrir mutaciones,
es decir, experimentar pequeños cambios en su información genótica, de manera
que exista mayor diversidad en la población.

A diferencia de los AGs, los EDAs carecen de operadores de cruza y mutación,
por lo que los nuevos individuos son generados mediante un modelo de probabilidad capaz de considerar dependencias entre las variables, el cual se encarga de
aproximar la distribución conjunta de una muestra de los mejores individuos de
la población.


El objetivo de esta investigación es el de proponer un algoritmo de estimación
de distribución (EDA), basado en el concepto de mezclas de distribuciones normales, con la finalidad de resolver problemas de optimización en un espacio de
búsqueda multidimensional con restricciones.

## Objetivos

Los objetivos que se plantearon al realizar esta investigación fueron:

### Objetivo General

Proponer un EDA basado en la mezcla de diferentes distribuciones normales
para resolver problemas de optimizacion con restricciones.

### Objetivos Específicos

* Estudiar los diferentes tipos de EDA que existen con la intención de adquirir
un conocimiento más detallado sobre su funcionamiento.
* Analizar diferentes técnicas de penalización que permitan trabajar con algoritmos
evolutivos en espacios de búsqueda multidimensionales con restricciones.
* Implementar un algoritmo capaz de estimar una función de probabilidad,
mediante la mezcla de varias distribuciones normales.
