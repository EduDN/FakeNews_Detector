# FakeNews_Detector

# "Cazadores de Fake News"

## Descripción

Este repositorio contiene el código desarrollado para el taller "Cazadores de Fake News" organizado por la Universidad Anáhuac. El código se centra en la detección de noticias falsas utilizando la técnica de TF-IDF (Term Frequency-Inverse Document Frequency) y un clasificador Naive Bayes multinomial.

## Contexto

El conjunto de datos utilizado para este proyecto se basa en noticias del año 2017 provenientes de fuentes en los Estados Unidos de América (EE. UU.).

## Contenido del Repositorio

### 1. [Código en Google Colab](/codigo_fake_news_detection.ipynb)

- Este archivo contiene el código fuente completo en un entorno de Google Colab. Incluye importaciones de módulos, construcción de DataFrame, preprocesamiento de texto, entrenamiento de modelos y funciones adicionales para visualización.

### 2. [Dataset](/DATASET_NEWS.csv)

- El archivo CSV "DATASET_NEWS.csv" contiene el conjunto de datos utilizado para entrenar y probar el modelo. Este conjunto de datos contiene columnas de texto y etiquetas que indican si una noticia es falsa o real.

### 3. [Imágenes](/imagenes/)

- Esta carpeta contiene las nubes de palabras generadas para noticias reales y falsas.

## Instrucciones de Uso

1. **Construcción del DataFrame y Conjuntos de Entrenamiento/Prueba:**
   - El código comienza con la carga del conjunto de datos desde el archivo "DATASET_NEWS.csv". A continuación, se dividen los datos en conjuntos de entrenamiento y prueba.

2. **TF-IDF Vectorizer para la Clasificación de Texto:**
   - Se utiliza el TfidfVectorizer para convertir el texto en representaciones numéricas basadas en la frecuencia de términos.

3. **Entrenamiento del Modelo "Fake News":**
   - Se instancia un clasificador Naive Bayes multinomial y se entrena con los datos de entrenamiento.

4. **Inspección del Modelo:**
   - Se muestran las características más asociadas con noticias falsas y reales.

5. **Generación de Nubes de Palabras:**
   - Se generan nubes de palabras para visualizar las palabras más frecuentes en noticias falsas y reales.

6. **Predicción de Noticias:**
   - El usuario puede ingresar el título y contenido de una noticia para predecir su veracidad.

## Ejecución del Código

Para ejecutar este código, se recomienda utilizar un entorno de Google Colab o configurar un entorno local con las bibliotecas requeridas.

## Contribuciones

Siéntase libre de contribuir al repositorio mediante sugerencias, correcciones o mejoras. Las contribuciones son bienvenidas y apreciadas.

## Autores

- [Eduardo Domínguez Navarrete]([https://github.com/username](https://github.com/EduDN)) - 

## Licencia

Este proyecto está bajo la [Licencia MIT](/LICENSE).

---

¡Esperamos que este código sea útil para la detección de noticias falsas y enriquezca la experiencia de los participantes del taller "Cazadores de Fake News"!
