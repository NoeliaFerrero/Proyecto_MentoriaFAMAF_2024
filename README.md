# Mentoria FAMAF 2024 

# Proyecto: ***Sin bajar la Guard.IA ~ Construyendo conocimiento al servicio de la salud***

<div align="center">

<p align="center">
  <img src="https://github.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2024/blob/main/banner_proyecto.png">
</p>
</div>

# Tabla de contenidos 📖
- [Introduccion](#introduccion)
- [Contexto Sanitario](#Contexto_Sanitario)
  - [Objetivo](#objetivo)
- [Contexto Analítico](#Contexto_Analítico)
  - [Diccionario de Datos](#diccionario_de_datos)
  - [Vista previa de los datos](#vista_previa_de_los_datos)
- [FAQs](#faqs)
  - [¿Qué te sumaría participar en este proyecto?](#faq1)
  - [Este proyecto es para vos si...](#faq2)

## Introduccion 

Al igual que, un centro de atención médica puede ser el inicio de innumerables historias de recuperación, un buen proyecto de Ciencia de Datos, representa el punto de partida para decisiones informadas, ideas innovadoras y, finalmente, historias de éxito en salud.

Quien ha estado en la guardia de un hospital y se detuvo frente al panel de monitoreo de pacientes, sabe que cada minuto cuenta…que cada escenario es muy cambiante...
Esa pantalla, aparentemente un conjunto de datos fríos para algunos, es en realidad el equivalente a un sinfín de desenlaces para aquellos que saben interpretarla, donde cada diagnóstico es un **capítulo en la vida de una persona**.

Esta experiencia nos lleva a reflexionar sobre el poder de los datos en un mundo donde los recursos asociados a la salud de la población, en muchas ocasiones no son gestionados de la manera más efectiva.

En este proyecto de Ciencia de Datos, al igual que, en ese panel de monitoreo, no solo mostraremos cifras, nos comprometemos a generar hallazgos. Pero, ¿cómo podemos asegurarnos de que ese conocimiento realmente 'hable' y comunique esa información de manera asertiva?

La Guard.IA esta a punto de comenzar y el desafio mayor consiste en poner en marcha tanto las habilidades técnicas, como las habilidades blandas, que nos permitan ir desandando a lo largo del camino, todo lo que los datos recolectados, tienen para contar. 

## Contexto_Sanitario 

### Objetivo 

El objetivo principal del proyecto es utilizar técnicas de Ciencia de Datos para analizar y comprender la distribución de los establecimientos de salud y las especialidades médicas en todo el país. A partir de este análisis, se busca generar conocimientos que puedan ser utilizados para mejorar la planificación y la gestión de los recursos de salud a nivel nacional y provincial, así como para identificar posibles áreas de mejora (vulnerabilidad sanitaria).  

**[⬆ Volver al inicio](#introduccion)**

## Contexto_Analítico 

Para el desarrollo de este proyecto se construyeron los siguientes dataset: 

1.	Establecimientos de salud, con y sin internación, de todas las provincias y cuyo financiamiento es de origen público o de origen privado: Dataset conteniendo la mayor cantidad posible de establecimientos de salud de todo el país, con 40.682 registros resultantes luego de la integración. 
2.	Médicos por jurisdicción según domicilio electoral: Información consolidada de las distintas especialidades médicas a nivel federal, según jurisdicción constatada por padrón electoral, con 76 registros discriminados por provincia.
   
En ambos casos, se requirió la descarga, limpieza y consistencia de diferentes fuentes de datos oficiales: 

📌 Base nacional de Hospitales y Centros de Atención Primaria: la misma fue compilada por el Sistema de Información Sanitaria Argentina (SISA), obtenido a través del SEDRONAR en el sitio de IDERA (http://catalogo.idera.gob.ar). 

📌 Establecimientos de salud del programa SUMAR: El sitio fue scrapeado para la obtención de los listados de los establecimientos con la dirección de cada centro de salud. 

📌 Listados de hospitales y centros de atención de salud del Programa Nacional de Salud Sexual y Procreación Responsable (Ministerio de Salud) 

📌 Otras fuentes a nivel provincial, generalmente, Ministerios o Secretarías de Salud. 


Tipo de Archivo | Tamaño | Etiquetas | Estructura de Datos | N° Registros | N° Campos | Link |
|---|---|---|---|---|---|---|
| .CSV | 4,52 Mb| `Establecimientos, Geopandas`   | Tabular | 40.682  | 17 | [Link](https://github.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2024/blob/932398f852ae3619dedc304d591dc37b4fd871fd/DataSets/Establecimientos-asistenciales-asentados-registro-federal-refes-20220404.csv)|
| .CSV | 20   Kb| `Especialidades Médicas`        | Tabular | 76      | 25 | [Link](https://github.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2024/blob/main/DataSets/Cant_medicos%20especialistas%20por%20Provincia.csv)|

### Diccionario_de_Datos

|Nombre Archivo | Link |
|---|---|
| Descrip_Data | [Link](https://github.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2024/blob/1934d95136ef5f2b25d6d71cb2c856353699ece8/DataSets/Descrip_data.csv)|


### Vista_previa_de_los_Datos 

|Notebook | Descripción | Link |
|---|---|---|
| 🐍 Proyecto Sin bajar la Guard.IA | Demo de conexión a los Set de datos | [Link](------https://colab.research.google.com/drive/11ix1h6kQFJaYX3G78KJz68CCpWfgffML?usp=sharing) |
 
**[⬆ Volver al inicio](#introduccion)**

## FAQs

Si te interesó la temática del proyecto, me gustaría compartirte algunas 'Advertencias y Precauciones' relacionadas con la modalidad de trabajo de esta Guard.IA, así podrás tenerlas en cuenta antes de sumergirte en el proyecto...

### Faq1 


***Posología y forma de administración de los resultados hallados durante la mentoria***

🎯  El contexto es clave: proporcionar contexto es el equivalente a brindar un mapa de un hospital. Ayuda tanto a los involucrados en el proyecto, como a cualquier persona externa que tenga alcance al mismo, a “scrollear” a través de los datos, comprendiendo no solo el qué, sino el porqué. 

🩺  Claridad ante todo: al igual que una señal clara de emergencia, nuestros hallazgos deben destacar la información más crítica de manera comprensible a primera vista. La simplicidad muchas veces, no resta valor, lo amplifica. Se trabajará con la Metodología del Diamante como una forma de empezar a detectar/ampliar las ideas iniciales. 

### Faq2 

***Este proyecto esta CONTRAINDICADO para vos en caso de que...***

🚨  NO estes dispuesto/a a iterar end-to-end tantas veces como sea necesario y NO disfrutes afrontar los desafíos que implican los algoritmos de Machine Learning: al igual que los registros médicos interactivos, trabajaremos con las distintas funcionalidades de las librerías para Ciencia de Datos, que nos permitan desarrollar modelos capaces de interpretar y aprender de la naturaleza de los datos seleccionados. Además, apuntando a un enfoque multidimensional y poniendo el foco en las preguntas de interés, cruzaremos los datos bajo estudio con los datos obtenidos en el Censo Nacional 2022 y con información compatible de la API de Google para georreferenciar los establecimientos de salud. Y a medida que vallamos avanzado en el proyecto, se trasladaran los insights obtenidos al framework de Streamlit para convertir los scripts en una data apps y poder mostrarlos de manera más interactiva. Todo en Python puro y open source, no se requiere experiencia en front-end. Trabajando con Generative IA + Steamlit, lograremos el match perfecto.

💊  NO te guste crear visualizaciones con propósito y presentaciones atractivas: los colores y el diseño de la cartelería empleada en un establecimiento hospitalario, claramente no son solo estéticos. Son señales visuales que guían la atención, resaltan diferencias críticas y evocan experiencias. De igual manera, se abordará el proyecto mediante técnicas de storytelling (narrativa visual), por ejemplo, usando atributos preatentivos, esto es, atributos visuales que nuestro cerebro procesa sin necesidad de una acción consciente y trabajaremos con mapas, mapas y mas mapas.

🚑  NO te comprometas a trabajar en equipo: El compromiso es un aspecto que a menudo se pasa por alto en los esfuerzos de colaboración y es fundamental para conseguir resultados de calidad entre las personas que trabajan en un tema concreto. Será necesario dedicar el tiempo suficiente para generar buenos aportes al proyecto, así como para apoyar las iniciativas de todos los integrantes de la mentoría.


**[⬆ Volver al inicio](#introduccion)**

Gracias por haberte detenido en estas coordenadas, espero que te lleves algo útil del tiempo invertido ;) 

By Noe Ferrero
