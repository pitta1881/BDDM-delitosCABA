# INTRODUCCIÓN
El análisis y predicción de delitos en entornos urbanos es un desafío clave para la seguridad pública y la planificación estratégica. A través del uso de modelos de aprendizaje supervisado y técnicas de clustering, es posible identificar patrones delictivos, agrupar incidentes con características similares y anticipar la ocurrencia de eventos criminales en función de variables temporales, espaciales y contextuales. Este proyecto busca desarrollar un modelo capaz de predecir, clasificar y agrupar delitos urbanos a partir de datos históricos, mejorando la toma de decisiones en materia de prevención del crimen.

# MOTIVACIÓN
La propuesta se fundamenta en dos pilares principales:
* **Aplicación de conocimientos adquiridos**: Implementar técnicas avanzadas de aprendizaje supervisado y clustering, aplicando herramientas y algoritmos complejos en un problema real.
* **Impacto social**: Desarrollar un sistema de análisis delictivo que contribuya a mejorar la seguridad ciudadana y **permita alertar** a los usuarios cuando se encuentren en una zona y horario de alta incidencia delictiva.

# OBJETIVO GENERAL
Desarrollar modelos de machine learning que permitan analizar y comprender los delitos urbanos registrados en CABA durante 2016-2022, identificando patrones espacio-temporales y estimando la probabilidad de ocurrencia de nuevos delitos

# OBJETIVOS ESPECÍFICOS
* Aplicar el proceso de KDD en un conjunto de datos de delitos urbanos.
* Implementar y entrenar un modelo de aprendizaje supervisado para predecir la ocurrencia de delitos según características espacio-temporales.
* Aplicar técnicas de clustering para la tipificación de delitos con características similares.
* Evaluar el desempeño del modelo mediante métricas como Exactitud, F1-Score y Matriz de Confusión, e iterando para calibrar el modelo.
* Construir un índice de peligrosidad temporal basado en la estimación de probabilidades.
* Explorar la integración de fuentes de datos adicionales para enriquecer el análisis, como la distancia a espacios verdes, comisarías y escuelas.
* Incorporar análisis de noticias sobre barrios peligrosos para contextualizar los hallazgos.

# METODOLOGÍA
### 1. Adquisición de Datos  
Se utilizarán datos abiertos de delitos registrados en una ciudad, conteniendo información como: 
* Fecha y hora del delito. 
* Ubicación geográfica (barrio, comuna, coordenadas GPS). 
* Tipo y subtipo de delito. 
* Uso de arma y/o moto.
* Distancia a espacios verdes, comisarías y escuelas.
### 2. Preprocesamiento de Datos  
* Limpieza de datos y manejo de valores nulos o inconsistentes
* Normalización y transformación de variables categóricas en numéricas. 
* Ingeniería de características para la generación de nuevas variables relevantes.
* Análisis exploratorio de noticias sobre zonas de alta criminalidad 
### 3. Entrenamiento del Modelo  
Se investigarán e implementarán distintos algoritmos de aprendizaje supervisado y clustering, como: 
* Regresión logística para predecir la ocurrencia y probabilidad de delitos en una zona y franja horaria. 
* Random Forest para clasificación del tipo de delito. 
* K-Means o DBSCAN de acuerdo a los resultados del análisis de los datos, para identificar grupos de delitos con características similares y analizar hotspots del crimen. 
### 4. Evaluación y Ajuste  
Se medirán métricas de desempeño como: 
* Exactitud, Recall y F1-Score. 
* Matriz de Confusión para analizar errores de clasificación. 
* Análisis de la cohesión y separación en los clusters obtenidos. 
* Comparación de modelos para seleccionar el más efectivo.
