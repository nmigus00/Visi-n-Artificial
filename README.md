# Visión-Artificial - Face Detection

Este es el enalce para la carpeta de trabajo con los dataets y el código:
https://drive.google.com/drive/folders/1AUmAc6wzIIcPzUWBzpo04FI79yyawfxe?usp=sharing

Esta es una guía para la ejecución del código de detección de rostros en el método Tradicional.

Un Pipeline de la ejecución del código:

Al principio encontramos el código necesario para conectar con el Drive para luego poder acceder a la 
ruta dónde encontramos los diferentes Datasets que hemos utilizado. 

Después encontramos los diferentes códigos para ejecutar cada Dataset. No tienen nada diferente el uno del otro porque trabajamos sobre un mismo modelo.

En la primera ejecución trabajamos con el Dataset de Widder con el que entrenamos nuestro modelo de HOG Histograms y SVM y mejorando los resultados con Adaboost.
No hemos podido obtener resultados de entrenamiento y de una posterior evaluación debido a que al principio tuvimos que trabajar con otro dataset,
que al final no podíamos utilizar y tampoco disponíamos del código necesario.

En la segunda ejecución ya con el modelo guardado queríamos evaluarlo con el segundo Dataset el que cambiamos por uno de los que primero habíamos escogido, porque el dataset no tenía los formatos correctos. Trabajando con el Dataset de FDDB que no pudimos evaluar debido al tiempo de ejecución del entrenamiento y que no se pudo ejecutar y a veces se finalizaba la ejecución por falta de espacio.

Aunque no dispusimos del tiempo necesario para la ejecución de los códigos por los cambios en los Dataset estos serían los pasos a la hora de ejecutarlo todo.

IMPORTANTE: Para una correcta ejecución se deben modificar las rutas de los dos códigos. Los dos códigos tienen sus respèctivas anotaciones de las imágenes en un .txt.
