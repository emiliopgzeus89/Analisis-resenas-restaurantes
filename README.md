# Proyecto de comparación de modelos preentrenados para análisis de sentimientos

## Opiniones de restaurantes mediante modelos de Hugging Face y procesamiento de lenguaje natural (NLP)

\---

# Título y descripción

## Nombre del proyecto

Comparación de modelos preentrenados de Hugging Face para análisis de sentimientos en opiniones de restaurantes.

## Objetivo general

Comparar el desempeño de tres modelos preentrenados de procesamiento de lenguaje natural para identificar sentimientos en reseñas de restaurantes y determinar cuál ofrece el mejor equilibrio entre precisión y eficiencia computacional.

## Contexto general

El análisis de sentimientos permite identificar la percepción de los clientes a partir de comentarios escritos. En este proyecto se evaluaron tres modelos preentrenados disponibles en Hugging Face para clasificar opiniones de restaurantes en categorías de sentimiento. La comparación se realizó mediante métricas de desempeño y tiempos de inferencia, con la finalidad de identificar la alternativa más adecuada para aplicaciones prácticas de análisis de opiniones.

## Enfoque de inteligencia artificial

* Tipo de aprendizaje: supervisado.
* Dominio: procesamiento de lenguaje natural (NLP).
* Enfoque: análisis de sentimientos.
* Estrategia: evaluación comparativa de modelos preentrenados.
* Modelos evaluados:

  * RoBERTuito Sentiment Analysis.
  * DistilBERT Multilingual Sentiment Analysis.
  * XLM-RoBERTa Sentiment Analysis.

\---

# Tecnologías utilizadas

## Lenguaje de programación

* Python 3.x

## Librerías principales

* Pandas
* NumPy
* Transformers (Hugging Face)
* Scikit-learn
* Matplotlib
* Seaborn

## Herramientas de desarrollo

* Google Colab
* GPU NVIDIA T4
* Hugging Face Hub

\---

# 

# Estructura del proyecto

├── data/                  # Dataset de opiniones de restaurantes
├── notebooks/             # Desarrollo y pruebas en Google Colab
├── results/               # Métricas, gráficas y matrices de confusión
├── README.md              # Documentación del proyecto
└── requirements.txt       # Dependencias del proyecto

# Instrucciones de uso

## Instalación de dependencias

 * Abrir Google Colab.
 * Activar el entorno de ejecución con GPU.
 * Instalar las dependencias necesarias.
 * Verificar la disponibilidad de la GPU.
 * Cargar el archivo de opiniones de restaurantes.

# Ejecución del código

Nota: Las celdas deben ejecutarse en el orden establecido para garantizar la correcta evaluación de los modelos.

 * Celda 1: Importación de librerías.
 * Celda 2: Carga y exploración del dataset.
 * Celda 3: Preparación de los datos.
 * Celda 4: Carga de modelos preentrenados.
 * Celda 5: Inferencia y clasificación de opiniones.
 * Celda 6: Normalización de etiquetas.
 * Celda 7: Evaluación mediante métricas.
 * Celda 8: Generación de matrices de confusión.
 * Celda 9: Comparación gráfica de resultados.
 * Celda 10: Análisis de tiempos de inferencia.

# Limitaciones del proyecto
 * El conjunto de datos utilizado representa únicamente una muestra de opiniones de restaurantes.
 * Los modelos fueron utilizados en su versión preentrenada sin ajuste fino (fine-tuning).
 * El desempeño puede variar dependiendo del idioma, longitud y contexto de las reseñas.
 * Los resultados dependen de la calidad y distribución de las opiniones evaluadas.
 * La ejecución se realizó en Google Colab, por lo que los tiempos de procesamiento pueden variar en otros entornos computacionales.

# Resultados obtenidos
## Métricas utilizadas

 * Accuracy
 * Precision
 * Recall
 * F1-score
 * Tiempo de inferencia

# Análisis de resultados

La evaluación permitió identificar diferencias significativas entre los modelos analizados. Los tres fueron capaces de clasificar opiniones positivas, negativas y neutrales; sin embargo, se observaron variaciones en su precisión y velocidad de procesamiento.

Las matrices de confusión mostraron que la clasificación de opiniones neutrales representa el principal desafío para los modelos evaluados, debido a la ambigüedad presente en este tipo de comentarios. Asimismo, las gráficas comparativas facilitaron la visualización de las diferencias en desempeño y eficiencia.

La combinación de métricas de clasificación y tiempos de inferencia permitió identificar el modelo con mejor equilibrio entre exactitud y costo computacional, cumpliendo satisfactoriamente el objetivo planteado para el proyecto.

# Conclusiones

Los resultados obtenidos demuestran que los modelos preentrenados de Hugging Face constituyen una alternativa eficiente para implementar sistemas de análisis de sentimientos sin necesidad de entrenar modelos desde cero.

La comparación realizada permitió evaluar objetivamente el desempeño de cada alternativa mediante indicadores cuantitativos y herramientas visuales. Además, se comprobó que la selección de un modelo debe considerar no solo la precisión de clasificación, sino también factores como el tiempo de respuesta y los recursos computacionales requeridos.

Finalmente, el proyecto valida la utilidad de las técnicas modernas de procesamiento de lenguaje natural para apoyar la toma de decisiones basada en la opinión de los clientes y sienta las bases para futuras mejoras mediante técnicas de fine-tuning y la incorporación de conjuntos de datos más amplios.

Créditos

Autor: Emilio Páez García
Institución: Universidad Tecmilenio
Materia: Gestión de Proyectos de Inteligencia Artificial
Actividad: Comparación de Modelos Preentrenados de Hugging Face para Análisis de Sentimientos
Fecha: Octubre de 2026


