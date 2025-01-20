# Análisis de Datos sobre COVID-19: Respuestas a Preguntas Clave

¡Bienvenido al proyecto de análisis de datos sobre el COVID-19! Este proyecto tiene como objetivo analizar la evolución de la pandemia utilizando los datos proporcionados por la Universidad Johns Hopkins. Aquí podrás encontrar el proceso de limpieza, preparación y visualización de los datos, con el fin de responder a preguntas clave sobre los contagios a nivel mundial.

## 🌍 Descripción del Proyecto

Este proyecto se enfoca en el análisis de los datos globales sobre el COVID-19, utilizando la base de datos proporcionada por la Universidad Johns Hopkins. El objetivo es responder a tres preguntas clave relacionadas con la evolución de la pandemia:

1. **¿En cuál mes se presentó el mayor número de contagios?**
2. **¿En ese mismo mes, cuál fue el país que reportó más contagios?**
3. **¿Cuál es el país con el menor número de casos reportados hasta la fecha?**

A través de este análisis, buscamos no solo entender mejor cómo se ha propagado el virus, sino también presentar los datos de manera accesible para todos. Las gráficas generadas permiten visualizar de forma clara la evolución de la pandemia y resaltar patrones importantes, tanto a nivel global como en países específicos.

El proyecto utiliza herramientas de ciencia de datos como Python, Pandas y Matplotlib, lo que permite manejar, limpiar y visualizar grandes volúmenes de datos de manera eficiente. Si bien el enfoque es técnico, la presentación de los resultados está diseñada para ser fácilmente comprendida, sin necesidad de un conocimiento profundo en análisis de datos.

Este es un ejercicio práctico para aplicar los conocimientos adquiridos en el análisis de datos, y es parte de un esfuerzo por contribuir al entendimiento global de la crisis sanitaria, mostrando la información de una manera clara y comprensible para todos.

## 📊 Datos Utilizados

Los datos utilizados para este análisis provienen de la base de datos pública de la **Universidad Johns Hopkins**, que contiene información detallada sobre los casos confirmados de COVID-19 a nivel mundial. Puedes acceder al dataset a través del siguiente enlace:

[Dataset de la Universidad Johns Hopkins - Casos Confirmados](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

### 📜 Condiciones de Uso del Dataset

El dataset de la Universidad Johns Hopkins está disponible bajo las siguientes condiciones. Puedes revisar el archivo de condiciones de uso en el siguiente enlace:

[Condiciones de Uso - Johns Hopkins COVID-19 Data](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

## 🚨 Contexto

El **SARS-COV-2**, responsable de la enfermedad **COVID-19**, es un virus de la familia de los coronavirus que apareció en China a finales del año 2019 y se expandió a gran velocidad a lo largo y ancho del globo, sorprendiendo a la mayoría de países del planeta y causando una pandemia a inicios de 2020. 

La gran preocupación con respecto a este virus es su **alto índice de contagio**, lo que le permitió tal expansión en un período muy corto de tiempo; y su **alto grado de afectación** en pacientes con comorbilidades previas, al punto de ocasionar la muerte rápidamente. Esta pandemia ha puesto a prueba la capacidad de respuesta de los sistemas de salud de todo el mundo y ha cambiado profundamente las dinámicas sociales y económicas a nivel global.

## 🔧 Tecnologías y Herramientas Usadas

Este proyecto se desarrolló utilizando las siguientes herramientas y bibliotecas:

- **Python 3**: Lenguaje de programación utilizado para procesar los datos.
- **Pandas**: Biblioteca principal para la manipulación y limpieza de datos.
- **Matplotlib**: Herramienta para la visualización de datos en gráficos.
- **Jupyter Notebook**: Entorno interactivo donde se realizaron los análisis y visualizaciones.

## 📈 Metodología

1. **Carga de los Datos**: Los datos de casos confirmados, decesos y recuperados de COVID-19 se obtuvieron desde la base de datos pública de la Universidad Johns Hopkins.
2. **Limpieza de los Datos**: Se trató y transformó la información para que fuera adecuada para el análisis, manejando valores nulos, cambiando formatos de fecha, y agrupando los datos por mes y país.
3. **Análisis**: Utilizamos técnicas de análisis para obtener respuestas a las preguntas planteadas sobre los contagios globales.

## 📊 Resultados Clave

- **Mes con el mayor número de contagios**: El mes con el mayor número de contagios es: Enero del año 2022, con 87136808.0 contagios.
- **País con más contagios en ese mes**: En 1/2022, el país con más contagios fue US, con 20336435.0 contagios.
- **País con el menor número de casos reportados hasta la fecha**: El país con el menor número de casos reportados es: Korea, North, con 1 contagio.

## 🚀 ¿Cómo Ejecutar el Proyecto?

Si deseas ejecutar este análisis en tu propia máquina, sigue estos pasos:

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/usuario/analisis-covid-19.git
