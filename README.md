# Especializacion Universidad de Antioquia
# Monografia

# Título

Desarrollar una herramienta de análisis de sentimientos que pueda extraer información relevante de Google noticias en tiempo real para comprender la percepción pública sobre un tema específico.

# Descripción

Se llevará a cabo la implementación y entrenamiento de un modelo de Procesamiento del Lenguaje Natural (NLP) con la capacidad de predecir la categoría de un texto dado como positivo, neutro o negativo.

# Contenido

- DB_temp: Contiene la base de datos temporal a la cual se ha realizado preprocesamiento y que estará destianada a entrenar el modelo de word2vec.
- notebooks:
  - google_news_extract.ipynb: Utiliza librerias como GoogleNews y newspaper3k para realizar la extracción de datos de portales noticiosos
  - preprocesamiento.ipynb: Se describe diferentes formas de tokenización y preprocesamiento de palabras como stopwords.


#  Instrucciones de uso

- Clonar repositorio:
- https://github.com/CDspana/Especializacion.git

- Si desea conocer las Estructura Típica de Preprocesamiento para proyectos e NLP siga el notebook preprocesamiento.ipynb

  - Abrir el Notebook
  - jupyter notebook Word2Vec.ipynb

- Si desea extraer datos de google news siga el notebook google_news_extract.ipynb

  - Abrir el Notebook
  - jupyter notebook google_news_extract.ipynb

# Conclusiones:

- Se ha logrado avances significativos en la extracción de datos de google news, y se tiene confianza en superar las limitaciones de bloqueo de IP.
- Se ha logrado implementar exitosamente un pipeline de pre procesamiento tipico para proyectos de NLP
  
# Referencias:

[1] Mikolov, T., Sutskever, I., Chen, K., Corrado, G., & Dean, J. (2013). Distributed Representations of Words and Phrases and their Compositionality. arXiv [Cs.CL]. Retrieved from http://arxiv.org/abs/1310.4546

[2] Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient Estimation of Word Representations in Vector Space. arXiv [Cs.CL]. Retrieved from http://arxiv.org/abs/1301.3781

