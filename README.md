# TRABAJO-FINAL-MENTALIDAD-DE-CRECIMIENTO
Trabajo final de Mentalidad de Crecimiento  y Ccomunicacion
# De horas de trabajo manual a un proceso automatizado: mi experiencia con Power Query

## El desafío inicial

Durante uno de los proyectos que desarrollé en la carrera, tuve que analizar información de ventas y stock proveniente de distintas sucursales. El objetivo era reunir todos esos datos en un único tablero de control que permitiera visualizar la información mensual de manera ordenada y facilitar el análisis para la toma de decisiones.

## Cuando la limpieza de datos se convirtió en un problema

Al comenzar a revisar los archivos, noté que cada sucursal utilizaba un formato diferente. Algunas columnas tenían nombres distintos aunque representaban la misma información, había fechas mal cargadas, filas vacías y registros duplicados. En un principio decidí resolver estos inconvenientes manualmente, abriendo cada archivo en Excel y realizando las correcciones una por una.

Con el paso del tiempo, este método dejó de ser práctico. Además de requerir muchas horas de trabajo, aumentaba la posibilidad de cometer errores y hacía que cada actualización fuera prácticamente empezar de nuevo. La situación se volvió aún más compleja cuando la cantidad de registros superó las 50.000 filas, ya que Excel comenzó a responder con mucha lentitud. En ese momento entendí que necesitaba una solución diferente, capaz de adaptarse al crecimiento de la información.

## El cambio de estrategia

En lugar de continuar con un proceso manual, decidí aprovechar las herramientas que ofrece Power Query para automatizar la preparación de los datos. Antes de comenzar, analicé cuál era realmente el origen del problema y comprendí que el inconveniente principal no era el volumen de información, sino la falta de una estructura uniforme en los archivos recibidos.

A partir de ese análisis, diseñé una consulta que importaba automáticamente todos los archivos ubicados en una misma carpeta. Luego configuré una serie de transformaciones para unificar los nombres de las columnas, eliminar filas vacías y registros duplicados, corregir los formatos de fecha y asignar correctamente los tipos de datos, todo dentro de un único flujo automatizado.

Además, investigué el funcionamiento del **Query Folding**, una técnica que permite ejecutar determinadas transformaciones de la forma más eficiente posible, mejorando considerablemente el rendimiento del modelo y reduciendo los tiempos de procesamiento.

## Lo que aprendí de esta experiencia

Este proyecto me permitió cambiar mi forma de trabajar con los datos. Comprendí que la limpieza de información no debería depender de tareas repetitivas realizadas manualmente, sino de procesos automatizados que garanticen consistencia, rapidez y facilidad de mantenimiento.

También descubrí que entender el Lenguaje M aporta un valor muy importante, ya que permite ir más allá de las opciones disponibles en la interfaz gráfica de Power Query y optimizar cada transformación según las necesidades del proyecto.

Hoy considero que este aprendizaje no solo me ayudó a resolver un problema puntual, sino que también fortaleció mi forma de enfrentar nuevos desafíos, buscando siempre soluciones más eficientes, escalables y sostenibles.
## Lo que aprendí a partir del feedback

Durante la primera entrega de este proyecto recibí una devolución muy sincera sobre el trabajo realizado. Si bien el proceso cumplía con su objetivo, me señalaron que el código en Lenguaje M generado automáticamente por Power Query contenía varios pasos innecesarios. Por ejemplo, algunas transformaciones, como el cambio de tipo de datos, se repetían varias veces dentro de la misma consulta, lo que hacía que el procesamiento fuera más lento.

En un primer momento esa devolución me generó cierta frustración, ya que había dedicado mucho tiempo a desarrollar la solución. Sin embargo, después de analizar los comentarios comprendí que el objetivo del feedback no era cuestionar mi trabajo, sino ayudarme a mejorarlo. Esa forma de verlo me permitió adoptar una mentalidad de crecimiento y aprovechar la crítica como una oportunidad para seguir aprendiendo.

A partir de esas observaciones revisé el editor avanzado, eliminé las instrucciones que no aportaban valor y simplifiqué varias transformaciones para reducir la cantidad de pasos. Gracias a esos cambios conseguí un proceso más ordenado, un mejor rendimiento en la carga de datos y un modelo mucho más eficiente y profesional.

Esta experiencia me enseñó que aceptar las críticas constructivas y estar dispuesto a revisar el propio trabajo es una parte fundamental del aprendizaje y del desarrollo profesional.


