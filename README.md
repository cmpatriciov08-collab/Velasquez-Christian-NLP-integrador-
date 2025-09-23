# Análisis de NLP: Evolución Lírica en el Rock Argentino

## Descripción del Proyecto

Este proyecto explora la evolución lírica en la obra solista de tres figuras icónicas del rock argentino: **Charly García, Luis Alberto Spinetta y Fito Páez**, analizando el período comprendido entre 1980 y 2009.

El estudio utiliza técnicas de Procesamiento de Lenguaje Natural (NLP) para cuantificar diferencias en el vocabulario y complejidad lírica entre los artistas, identificar patrones de evolución temporal y comparar la efectividad de diferentes métodos de análisis para textos musicales.

## 📊 Características del Corpus

- **Género**: Rock Argentino
- **Tamaño**: 24 letras de canciones (8 por artista)
- **Vocabulario**: ~4,162 palabras (lematizadas, sin stop words)
- **Fuente**: Rock.com.ar
- **Período**: 1980-2009
- **Artistas**: Charly García, Luis Alberto Spinetta, Fito Páez

## 🔬 Metodología de NLP Aplicada

### Técnicas Implementadas
- **Preprocesamiento**: limpieza de texto, tokenización, eliminación de stop words
- **Análisis léxico**: Bag of Words (BoW) y TF-IDF
- **Análisis semántico**: Word Embeddings (spaCy)
- **Análisis gramatical**: Tagging de Partes del Discurso (POS)
- **Análisis complementario**: Entidades Nombradas (NER) y análisis de sentimiento

## 📈 Hallazgos Principales

### 1. Estilos Lingüísticos Distintivos
- **Charly García**: Mayor uso de verbos, estilo más narrativo
- **Fito Páez**: Predominio de sustantivos, enfoque más objetual
- **Spinetta**: Balance con ligero predominio de adjetivos, lenguaje más descriptivo

### 2. Evolución Temporal del Corpus
Tendencia general hacia un lenguaje más descriptivo y conceptual en décadas posteriores, con aumento de sustantivos y adjetivos, y disminución relativa de verbos.

### 3. Efectividad de Métodos de NLP
- **Word Embeddings**: Superiores para capturar similitud semántica y afinidades temáticas
- **BoW/TF-IDF**: Efectivos para análisis de frecuencia y vocabulario explícito

## 🛠️ Stack Tecnológico

- **Lenguaje**: Python 3.x
- **Librerías principales**: 
  - `pandas`, `numpy` (análisis de datos)
  - `scikit-learn` (BoW, TF-IDF)
  - `spaCy` (word embeddings, POS tagging)
  - `matplotlib`, `seaborn` (visualizaciones)
  - `nltk` (procesamiento de texto)
  - `wordcloud` (visualización de palabras)

## 🚀 Instrucciones de Ejecución

### Prerrequisitos
```bash
# Instalar dependencias
pip install pandas numpy scikit-learn spacy matplotlib seaborn nltk wordcloud

# Descargar modelo de spaCy para español
python -m spacy download es_core_news_md

# Descargar recursos de NLTK
python -c "import nltk; nltk.download('stopwords'); nltk.download('punkt')"
```

### Ejecución del Proyecto
1. Clonar el repositorio (o descargar los archivos del proyecto)
2. Ejecutar el notebook Jupyter/Colab en orden secuencial
3. Los datos y resultados se generarán automáticamente

## 📋 Limitaciones y Trabajo Futuro

### Limitaciones Actuales
- Tamaño reducido del corpus limita la generalización de resultados
- Dificultad para analizar figuras retóricas complejas y sintaxis avanzada

### Extensiones Futuras
- **Modelado de temas** con LDA
- **Análisis de emociones** y sentimiento avanzado
- **Análisis sintáctico** detallado
- **Comparativa con otros géneros** y artistas
- Expansión del corpus con más canciones y períodos

## 👤 Autor

**Nombre del Autor**  
- GitHub: [@usuario](https://github.com/usuario)
- Email: contacto@email.com

**Trabajo Integrador - NLP**  
Fecha de realización: [Fecha del proyecto]

---

*Este proyecto forma parte de un estudio académico sobre aplicaciones de NLP en análisis musical y cultural.*

*Nota: Este análisis forma parte del trabajo integrador de Procesamiento del Lenguaje Natural, explorando técnicas computacionales para el estudio literario-musical.*
