Telecom X – Parte 2: Predicción de Cancelación de Clientes
Descripción del proyecto

Este proyecto corresponde a la segunda parte del desafío Telecom X, desarrollado dentro del programa de formación en ciencia de datos de Oracle Next Education en colaboración con Alura Latam.

El objetivo principal es desarrollar modelos de Machine Learning capaces de predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones. Para ello, se utilizan técnicas de preparación de datos, análisis exploratorio y modelado predictivo con el fin de identificar patrones que permitan anticipar el abandono de clientes y apoyar la toma de decisiones estratégicas.

Este trabajo se basa en el dataset previamente limpiado y preparado en la primera parte del desafío.

Objetivos

Preparar los datos para el entrenamiento de modelos predictivos.

Analizar la relación entre diferentes variables y la cancelación de clientes.

Construir modelos de clasificación para predecir churn.

Evaluar el rendimiento de los modelos mediante métricas de evaluación.

Identificar las variables que más influyen en la cancelación de clientes.

Proponer recomendaciones estratégicas basadas en los resultados obtenidos.

Tecnologías utilizadas

El proyecto fue desarrollado en Python utilizando las siguientes librerías:

pandas

numpy

matplotlib

seaborn

scikit-learn

Estas herramientas permiten realizar análisis de datos, visualización y desarrollo de modelos de machine learning.

Estructura del proyecto
TelecomX-Churn-Prediction
│
├── TelecomX_LATAM.ipynb
├── datos_tratados.csv
└── README.md

TelecomX_LATAM.ipynb contiene todo el proceso de análisis, preparación de datos y modelado.

datos_tratados.csv corresponde al dataset procesado en la primera parte del desafío.

README.md documenta el proyecto.

Metodología
Preparación de datos

Se utilizó el dataset previamente tratado en la primera parte del proyecto. En esta etapa se realizaron las siguientes acciones:

Eliminación de columnas que no aportan valor predictivo, como identificadores únicos.

Transformación de variables categóricas en variables numéricas mediante codificación one-hot.

Revisión de valores faltantes.

Preparación de los datos para su uso en modelos de machine learning.

Análisis exploratorio

Se realizó un análisis exploratorio para comprender el comportamiento de los clientes y detectar posibles patrones asociados a la cancelación.

Entre los análisis realizados se incluyen:

Distribución de clientes que cancelaron el servicio frente a aquellos que permanecen activos.

Matriz de correlación entre variables.

Visualización de relaciones entre variables relevantes como el tiempo de permanencia, los cargos mensuales y el tipo de contrato.

División del conjunto de datos

Para evaluar el desempeño de los modelos se dividió el dataset en:

70% de datos de entrenamiento

30% de datos de prueba

Esto permite medir la capacidad de los modelos para generalizar a datos no utilizados durante el entrenamiento.

Modelos utilizados

Se entrenaron diferentes modelos de clasificación para predecir la cancelación de clientes.

Regresión Logística

Este modelo permite estimar la probabilidad de que un cliente cancele el servicio a partir de diferentes variables explicativas.

Random Forest

Este modelo utiliza un conjunto de árboles de decisión para mejorar la capacidad de predicción y reducir el riesgo de sobreajuste.

Evaluación de los modelos

El rendimiento de los modelos se evaluó mediante las siguientes métricas:

Accuracy

Precision

Recall

F1-score

Matriz de confusión

Estas métricas permiten analizar la capacidad del modelo para identificar correctamente los casos de cancelación.

Importancia de variables

A partir del modelo Random Forest se analizó la importancia relativa de las variables para la predicción del churn. Este análisis permite identificar qué factores tienen mayor influencia en la decisión de cancelación de los clientes.

Entre las variables más relevantes se encuentran:

tipo de contrato

cargos mensuales

tiempo de permanencia del cliente

servicios contratados

Conclusiones

El análisis realizado permitió identificar patrones importantes relacionados con la cancelación de clientes.

Se observó que los clientes con contratos mensuales, cargos mensuales elevados y menor tiempo de permanencia presentan mayor probabilidad de cancelar el servicio.

Los modelos de machine learning permiten anticipar estos comportamientos y pueden utilizarse como herramienta para identificar clientes con mayor riesgo de abandono.

Recomendaciones

A partir de los resultados obtenidos se sugieren algunas estrategias orientadas a mejorar la retención de clientes:

promover contratos de mayor duración

ofrecer incentivos a clientes con alto riesgo de cancelación

implementar programas de fidelización

diseñar acciones preventivas basadas en análisis predictivo
