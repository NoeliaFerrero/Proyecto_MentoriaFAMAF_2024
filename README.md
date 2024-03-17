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
  - [Descripcion](#descripcion)
- [Contexto Analítico](#Contexto_Analítico)
  - [Diccionario de Datos](#diccionario_de_datos)
  - [Vista previa de los datos](#vista_previa_de_los_datos)
- [FAQs](#faqs)
  - [¿Qué te sumaría participar en este proyecto?](#faq1)
  - [Este proyecto es para vos si...](#faq2)

## Introduccion 

Así como una sala de emergencias es el punto de partida para innumerables historias de recuperación, un buen proyecto de Ciencia de Datos, es el punto de partida para decisiones informadas, ideas innovadoras y, finalmente, historias de éxito en salud.

Quien ha estado en un hospital y se detuvo frente al panel de monitoreo de pacientes, sabe cada minuto cuenta…que cada escenario es muy cambiante...
esa pantalla, aparentemente un conjunto de datos fríos para algunos, en realidad es una ventana hacia innumerables historias para aquellos que saben interpretarla: cada diagnóstico es el equivalente a un capítulo en la vida de una persona, donde generalmente se terminarán desencadenando un sinfín de desenlaces. 

Esta experiencia nos lleva a reflexionar sobre el poder de los datos en un mundo donde los recursos asociados a la salud de la población, en muchas ocasiones no son gestionados de la manera más efectiva.

En este proyecto de Ciencia de Datos, al igual que en ese panel de monitoreo, no solo mostraremos cifras, nos comprometemos a generar hallazgos. Pero, ¿cómo podemos asegurarnos de que ese conocimiento realmente 'hable' y comunique esa información de manera asertiva?

La Guard.IA esta a punto de comenzar y el desafio mayor consiste en poner en marcha tanto las habilidades técnicas, como las habilidades blandas, que nos permitan ir desandando a lo largo del camino, todo lo que los datos recolectados, tienen para contar. 

## Contexto_Sanitario 

### Objetivo

Gestión de servicios de salud, analizar y determinar puntos críticos de saturación a nivel establecimientos y especialidades médicas.

### Descripcion 

El objetivo principal del proyecto es utilizar técnicas de Ciencia de Datos para analizar y comprender la distribución de los establecimientos de salud y las especialidades médicas en todo el país. A partir de este análisis, se busca generar conocimientos que puedan ser utilizados para mejorar la planificación y la gestión de los recursos de salud a nivel nacional y provincial, así como para identificar posibles áreas de mejora (vulnerabilidad sanitaria).  

**[⬆ Volver al inicio](#introduccion)**

## Contexto_Analítico 

Registros de 120000+ vuelos de aerolíneas comerciales entre los años 2019 y septiembre del 2022 inclusive. Cada registro representa un solo vuelo, incluido el nombre de la aerolínea, el número de vuelo y el aeropuerto de origen / destino, así como los horarios de salida y llegada programados / reales.

Tipo de Archivo | Tamaño | Etiquetas | Estructura de Datos | N° Registros | N° Campos | Link |
|---|---|---|---|---|---|---|
| .CSV | 13,5 Mb| Series Temporales, Transporte, Geoespacial | Tabular | 127929 | 28 | [Link](https://raw.githubusercontent.com/NoeliaFerrero/Proyecto_MentoriaFAMAF_2023/main/DataSet%20Aeropuerto%20Jorge%20Newery.csv) |

### Diccionario_de_Datos

Nombre Campo | Breve descripcion | 
|---|---|
| Aero | Aerolínea | 
| Vuelo | Codigo de Vuelo | 
| Cshare | Código compartido (un vuelo puede ser realizado por empresas del mismo holding)| 
| Origen | Ruta del vuelo | 
| Via | Escala del vuelo | 
| STA | Horario programado de arribo | 
| Sug | Horario sugerido | 
| ETA | Estimated Time Arrival| 
| ATA | Actual Time Arrival | 
| Tipo | Codificación del tipo de vuelo | 
| Asignar |  | 
| Pos | Posición asignada al arribo| 
| Ter | Terminal en que opera el arribo | 
| Sec | Sector asociado a la terminal | 
| Rmk | Remark (Estado del vuelo) | 
| Cin | Cinta asignada para retirar equipajes| 
| L&F | Mostrador de reclamos de equipajes asignado al vuelo | 
| Pax | Cantidad de pasajeros | 
| Vip | si tiene o no pasajeros vip ese vuelo | 
| Mat | MAtricula de la aeronave| 
| Acft | Tipo de aeronave | 
| Obs. | Observaciones | 
| Aero | Empresa aerea asociada a la partida | 
| #Rot | Vuelo asociado a la partida| 
| Cabecera | Cabecera de pista donde operó el arribo | 
| año | Año de operación del vuelo | 
| mes | Mes de operación del vuelo | 
| Hora | Hora de operación del vuelo | 

### Vista_previa_de_los_Datos 

|Notebook | Descripción | Link |
|---|---|---|
| 🐍 Proyecto FAMAF Aeroparque Jorge Newbery | Demo de conexión al Set de datos | [Link](https://colab.research.google.com/drive/11ix1h6kQFJaYX3G78KJz68CCpWfgffML?usp=sharing) |
 
**[⬆ Volver al inicio](#introduccion)**

## FAQs

### Faq1 

***¿Qué te sumaría participar en este proyecto?***

El peor mito que me invadía, cuando comencé a conocer este “smart data”, es que la inspiración llega cuando quiere. Y digo esto, porque todos, en mayor ó menor medida, hemos tenido dudas al momento de encontrar esa GRAN idea que guie nuestro primer GRAN proyecto, pero si ponemos atención, podemos encontrar puntos de inspiración muy claros en nuestra vida y las cosas que nos llaman la atención, y entonces empiezan a surgir las preguntas interesantes…claro que, para poder responder esas preguntas, debemos tener algo que es muy necesario: **contexto**. El contexto lo podemos obtener de muchos lugares: de los que hacemos, de lo que queremos hacer, algunos también lo llaman **motivación** ó **propósito**. 

Te invito a explorar esas dimensiones construyendo juntos este proyecto para que puedas: 
-	Mejorar lo que ya haces en tu trabajo
-	Profesionalizar tu conocimiento sobre un tema del que quieras aprender
-	Solidificar los beneficios del trabajo en equipo. Un trabajo bien logrado, donde cada integrante, sea pieza fundamental

### Faq2 

***Este proyecto es para vos si...***

Este recurso ha sido pensado con la intención de brindarte la flexibilidad para encontrar tu propio camino...diseñar un viaje en el que puedas desarrollar e intercambiar habilidades del mundo real...
asique si ya comenzaste esa metamorfosis que te permite pensar como un verdadero Cientifico/a de datos y especialmente si te gusta volar con la imaginación (lease, hacer presentaciones anti-aburridas) podes sumarte a bordo, la hoja de ruta esta casi lista, solo falta agregar la pasión por los datos que cada uno quiera compartir!

**[⬆ Volver al inicio](#introduccion)**

Gracias por tu lectura. Espero que te lleves algo útil de tu paso por acá ;) 

By Noe Ferrero
