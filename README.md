# Telecon_x
Proyecto de Análisis de Churn de Clientes - Telecom X
📊 Visión General del Proyecto
Este repositorio alberga un proyecto de análisis de datos enfocado en comprender y mitigar la tasa de abandono de clientes (Churn) para Telecom X , una empresa ficticia del sector de las telecomunicaciones. Como parte del rol de Asistente de Análisis de Datos, el objetivo principal fue recopilar, limpiar, procesar y analizar los datos de los clientes para identificar los factores clave que contribuyen a la pérdida de usuarios.

El análisis exploratorio de datos (EDA) realizado en este proyecto sienta las bases para el desarrollo de futuros modelos predictivos de churn y la implementación de estrategias de retención más efectivas.

🎯 Objetivo del análisis
El problema central al que se enfrenta Telecom X es una alta tasa de cancelaciones de servicios. Este proyecto busca:

Identificar patrones y tendencias en los datos de los clientes que abandonan.
Determinar las variables clave (demográficas, de servicio, de contrato, de comportamiento de gasto) que están fuertemente correlacionadas con el abandono.
Extraer insights accionables que permiten al equipo de Data Science ya la gerencia de Telecom X comprender "por qué" los clientes se van y "qué" se puede hacer al respecto.
📂 Estructura del Repositorio
README.md: Este archivo, con una descripción general del proyecto.
Challenge Telecom X: análisis de evasión de clientes.ipynb: El archivo principal del proyecto que contiene todo el código Python, el análisis, las visualizaciones y el informe final.
df_final.csv: data frame final ya realizando toda la transformación de datos
🛠️ Herramientas y Librerías Utilizadas
El análisis se llevó a cabo utilizando el entorno de Python, con las siguientes librerías principales:

pandas: Para la manipulación y el procesamiento de datos.
numpy: Para operaciones numéricas eficientes.
matplotlib: Para la creación de gráficos y visualizaciones estáticas.
seaborn: Para la creación de visualizaciones estadísticas atractivas y complejas.
🚀 Pasos del análisis
El proyecto se estructuró en las siguientes fases clave:

Recopilación y Carga de Datos: Importación del conjunto de datos inicial (JSON) en un entorno de trabajo de Python.
Limpieza y Preprocesamiento de Datos:
Normalización de la estructura JSON.
Manejo de valores nulos/vacíos.
Conversión de tipos de datos.
Transformación de valores categóricos ('Sí'/'No' a 1/0).
Unión de DataFrames para crear un conjunto de datos único y consolidado.
Análisis Exploratorio de Datos (EDA):
Cálculo de la tasa general de abandono.
Análisis de la distribución de churn por variables categóricas.
Análisis de la distribución de churn por variables numéricas, utilizando estadísticas descriptivas, histogramas y diagramas de caja para identificar patrones.
