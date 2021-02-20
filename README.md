# Introducción a Spark

![](https://github.com/Meluiscruz/Intro_a_Spark/blob/master/Images/spark%20logo.png?raw=true)

## Metricas del proyecto.

![](https://img.shields.io/github/stars/Meluiscruz/Intro_a_Spark.svg) ![](https://img.shields.io/github/forks/Meluiscruz/Intro_a_Spark.svg)
![](https://img.shields.io/github/issues/Meluiscruz/Intro_a_Spark.svg)![](https://img.shields.io/github/tag/Meluiscruz/Intro_a_Spark.svg)

## Alcance y objetivos.

Este proyecto pertenece a una rama del repositorio del curso de [Introduccion de Spark de Platzi](https://github.com/terranigmark/curso-apache-spark-platzi "Introduccion de Spark de Platzi"), impartido por [Oscar Gutiérrez](https://github.com/Ator97 "Oscar Gutiérrez").

Las operaciones de Spark en este proyecto intentan expresar las capacidades del framework en el caso específico de relacionar diferentes data sets de deportistas olímpicos y sus estadisticas a lo largo de la historia de los Juegos olimpicos Modernos.

Las principales diferencias con respecto al repositorio original son las siguientes:

- Hay instrucciones detalladas sobre la instalación y configuración de Spark en Linux.
- Hay notas de Cornell sobre los modulos 1, 2 y 3 del curso.
- Los Jupyter Notebooks de los modulos 3 y 4 estan divididos por lecciones y poseen comentarios adicionales.

## Tabla de contenido.

- [/files](https://github.com/Meluiscruz/Intro_a_Spark/tree/master/files "files"): Directorio que contiene los datasets del proyecto.
- [/Images](https://github.com/Meluiscruz/Intro_a_Spark/tree/master/Images "Images"): Directorio de imagenes miscelanias, no relevante.
- [/Notebooks](https://github.com/Meluiscruz/Intro_a_Spark/tree/master/Notebooks "Notebooks"): Es donde habitan los Jupyter Notebooks y archivos html del proyecto.
  - [/Notebooks/Instrucciones_de_configuracion_y_uso](https://github.com/Meluiscruz/Intro_a_Spark/tree/master/Notebooks/Instrucciones_de_configuracion_y_uso "Instrucciones de config"): El archivo main.html indexa las notas de Cornell relativas a los modulos 1, 2 y 3 del curso. 
 
- [/codeExample.py](https://github.com/Meluiscruz/Intro_a_Spark/blob/master/codeExample.py "codeExample.py"): Es un ejemplo de script de pySpark que tiene dos propositos; comprobar la instalación del framework y demostrar lo impractico que es trabajar con scripts de pyspark en ambientes productivos. 

- [/data.csv](https://github.com/Meluiscruz/Intro_a_Spark/blob/master/data.csv "data.csv"): Dataset de prueba para la verificaci{on de la instalación del framework. 
  
## ¿Por qué desarrollé este proyecto?

Mi intensión es tener a la mano este material para futuras consultas, ya que tengo pensado utilizar Spark como framework de consulta y administración de bigdata. En un futuro no muy lejano estaré haciendo un pull request al repositorio original para que las notas sean parte del material oficial del curso.

## ¿Qué está pendiente por desarrollar?

Las notas de Cornell de los modulos 4 y 5. Así como profundizar en el Jupyter Notebook del modulo 5, ya que ese archivo se mantiene sin cambios con respecto a su versión original.

## Información técnica.

Los cuadernos estan desarrollados en Jupyter Notebooks, se utilizó un ambiente virtual con Python=3.7, compatible para la versión de Spark 2.4.7. Cabe recorad que Spark requiere de Scala y la máquina virtual de Java para funcionar, para mayor detalle consulte el siguiente [link](https://spark.apache.org/docs/2.4.7/ "documentación")
