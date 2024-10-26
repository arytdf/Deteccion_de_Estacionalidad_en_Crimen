![Politecnico](https://github.com/arytdf/Deteccion_de_Estacionalidad_en_Crimen/blob/main/src/visualization/Politecnico_Banner.jpg)
 **Carrera:** Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

 **Institucion:** Centro Politécnico Superior Malvinas Argentinas

 **Materia:** Aprendizaje Automático

 **Proyecto Aprendizaje Automatico:** Detección de Estacionalidad en Crimen

 **Alumno:** Ariel Martin Altamirano

 **Profesor de la Catedra:** Martin Mirabete
 <p align="center">
  <img src="https://komarev.com/ghpvc/?username=arytdf" alt="Vistas de perfil" />
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  </a>
</p>

# Detección de Estacionalidad en la Criminalidad de Tierra del Fuego

## Objetivo del Proyecto
El objetivo principal de este proyecto es implementar un modelo de análisis de series temporales para detectar patrones estacionales en la ocurrencia de diferentes tipos de delitos en la Provincia de Tierra del Fuego, AeIAS, durante los años 2014 a 2024. Mediante el uso de técnicas de aprendizaje automático y análisis estadístico, buscamos identificar tendencias recurrentes que permitan predecir aumentos o disminuciones en la incidencia delictiva de manera periódica, con el fin de ayudar a las autoridades locales en la toma de decisiones sobre la asignación de recursos policiales y el desarrollo de estrategias preventivas.

## Contexto del problema
La criminalidad y la incidencia de delitos son problemas persistentes en muchas sociedades. En la Provincia de Tierra del Fuego, AeIAS, la variación de delitos a lo largo del tiempo está influenciada por numerosos factores sociales, económicos y culturales, y se ha observado que la criminalidad puede tener componentes estacionales, con ciertos tipos de delitos ocurriendo con mayor frecuencia en determinados meses o estaciones del año. Por ejemplo, delitos como robos a la propiedad podrían ser más comunes durante el verano, mientras que otros tipos de delitos podrían aumentar en meses específicos debido a festividades o vacaciones.
Comprender estos patrones estacionales es crucial para poder anticipar aumentos en la actividad delictiva y tomar medidas preventivas de manera eficiente. Actualmente, la planificación de la seguridad se realiza, en gran medida, de manera reactiva, basada en el histórico de incidentes reportados. Al aplicar un análisis de series temporales, se podría transformar esta planificación en un proceso más proactivo, que permitiría a las fuerzas del orden estar mejor preparadas y optimizar la asignación de sus recursos.

## Preguntas de Investigación e Hipótesis
Este proyecto busca responder las siguientes preguntas de investigación:

1. ¿Existen patrones estacionales claros en la incidencia de ciertos tipos de delitos en la Provincia de Tierra del Fuego?
2. ¿Cuáles son los tipos de delitos que muestran una mayor valoración con ciertos meses o estaciones del año?
3. ¿Cómo pueden las tendencias estacionales ayudar a predecir aumentos en la actividad delictiva y apoyar la planificación de recursos policiales?

**Hipótesis:**

* **H1:** Existe una estacionalidad significativa en la ocurrencia de algunos tipos de delitos, con ciertos picos que se repiten en los mismos meses a lo largo de los años.
* **H2:** Los delitos contra la propiedad presentan una mayor incidencia durante los meses de verano, debido al aumento de actividad turística y menor supervisión de propiedades.
* **H3:** El análisis de series temporales puede predecir con una exactitud razonable los picos de actividad delictiva, facilitando una mejor distribución de los recursos de seguridad.

## Estructura del proyecto
La estructura del proyecto sigue un enfoque de ciencia de datos basado en cookiecutter e incluye:
* **Limpieza de datos:** Preparación y limpieza de los datos históricos de delitos.
* **Análisis exploratorio de datos (EDA):** Análisis preliminar para identificar patrones y tendencias.
* **Modelado:** Desarrollo de modelos de series temporales para capturar la estacionalidad en los datos.
* **Evaluación:** Validación de modelos para asegurar una predicción precisa.
* **Despliegue:** Preparación del modelo para su uso por las autoridades locales.

## Valor del proyecto
Este proyecto aportará valor al ayudar a las autoridades locales a tomar decisiones informadas y proactivas sobre la asignación de recursos policiales y el diseño de estrategias preventivas. Con una planificación basada en predicciones de estacionalidad, se pueden mitigar los picos de criminalidad y optimizar la seguridad pública en beneficio de la comunidad.


[English Version]

# Seasonal Crime Patterns in Tierra del Fuego

## Introduction
This project aims to implement a time series analysis model to detect seasonal patterns in the occurrence of different types of crimes in Tierra del Fuego, Argentina, from 2014 to 2024. Through machine learning and statistical analysis techniques, we seek to identify recurring trends that allow us to predict periodic increases or decreases in crime incidence, in order to support local authorities in making decisions about the allocation of police resources and the development of preventive strategies.

## Problem Context
Crime and the incidence of offenses are persistent problems in many societies. In the Province of Tierra del Fuego, the variation in the occurrence of crimes over time is influenced by various social, economic, and cultural factors. It has been observed that crime can have seasonal components, with certain types of crimes occurring more frequently in specific months or seasons of the year. 

**For example, property crimes such as theft may be more common during the summer, when there is more tourist activity and less property supervision.**

Other types of crimes may increase in specific months due to holidays or vacation periods. Understanding these seasonal patterns is crucial to anticipating increases in criminal activity and taking preventive measures efficiently.

## Research Questions
### Are there clear seasonal patterns in the incidence of certain types of crimes in the Province of Tierra del Fuego?
### Which types of crimes show a stronger correlation with specific months or seasons of the year?
### How can seasonal trends help predict increases in criminal activity and support the planning of police resources?

## Project Structure
The project structure follows a cookiecutter-based data science approach and includes:
* **Data cleaning:** Preparation and cleaning of historical crime data.
* **Exploratory data analysis (EDA):** Preliminary analysis to identify patterns and trends.
* **Modeling:** Development of time series models to capture seasonality in the data.
* **Evaluation:** Model validation to ensure accurate prediction.
* **Deployment:** Preparation of the model for use by local authorities.

## Project Value
This project will provide value by helping local authorities make informed and proactive decisions about the allocation of police resources and the design of preventive strategies. With planning based on seasonal predictions, crime spikes can be mitigated and public safety can be optimized for the benefit of the community.

**... (continue with the remaining sections of your project, such as results, technologies used, etc.)**


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
