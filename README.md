# Análisis de NLP: Evolución Lírica en el Rock Argentino (1980-2009)

## Descripción
Este análisis examina la evolución del vocabulario y la complejidad lírica en las carreras solistas de tres pilares del rock argentino: Charly García, Luis Alberto Spinetta y Fito Páez durante el período 1980-2009. El estudio busca identificar patrones lingüísticos cuantificables que demuestren cambios en la sofisticación literaria y el uso del lenguaje a lo largo de tres décadas de producción musical.

El análisis comparativo entre artistas revela diferencias significativas en sus estilos compositivos, validando las hipótesis iniciales sobre la evolución distintiva de cada artista. Spinetta mantiene una complejidad léxica estable, Charly García muestra una curva evolutiva marcada, y Fito Páez evidencia un crecimiento en diversidad vocabularia.

## Información del Corpus
- **Tipo**: Letras de canciones de rock argentino
- **Tamaño**: 24 textos (8 por artista), aproximadamente 4,162 palabras totales
- **Fuentes principales**: Rock.com.ar (extracción automatizada por web scraping)
- **Período temporal**: 1980-2009 (tres décadas de producción solista)
- **Criterios de selección**: Exclusivamente carreras solistas (excluyendo bandas anteriores), canciones de estudio publicadas oficialmente, balance temporal representativo

## Técnicas de NLP Aplicadas
- Preprocesamiento de texto (limpieza, tokenización, eliminación de stop words en español)
- Análisis de frecuencia léxica y diversidad vocabularia (TTR - Type-Token Ratio)
- Análisis con Bag of Words (BoW) y TF-IDF para identificar términos característicos
- Análisis con Word Embeddings (spaCy) para relaciones semánticas
- Análisis de sentimiento y emociones en las letras
- Análisis POS (Part-of-Speech) para complejidad gramatical

## Principales Hallazgos
- **Spinetta** confirma su perfil más "poético" con estabilidad en complejidad léxica a lo largo del tiempo, incluso en canciones aparentemente simples
- **Charly García** muestra el patrón evolutivo más marcado, con pico de complejidad en los 80 y simplificación progresiva hacia los 2000
- **Fito Páez** evidencia el crecimiento más significativo en diversidad vocabularia, validando la hipótesis de mayor sofisticación literaria en su obra madura
- **TF-IDF** resultó más efectivo que BoW para identificar términos distintivos por artista y período, mientras que los embeddings de spaCy revelaron relaciones semánticas interesantes en el uso metafórico

## Tecnologías Utilizadas
- Python 3.x
- pandas, numpy
- scikit-learn (BoW, TF-IDF, métricas de similitud)
- spaCy (modelo es_core_news_sm para español)
- NLTK (tokenización, stop words en español)
- matplotlib, seaborn (visualizaciones)
- requests, BeautifulSoup (web scraping inicial)

## Instrucciones de Reproducción
1. Clonar este repositorio
2. Instalar dependencias: `pip install -r requirements.txt`
3. Ejecutar el notebook: `jupyter notebook Trabajo_Integrador_Individual_NLP.ipynb`
4. Los datos ya están incluidos en la carpeta `mi_corpus/`

## Limitaciones y Trabajo Futuro
- **Principal limitación**: Tamaño reducido del corpus (24 canciones) limita la significancia estadística de algunos hallazgos
- **Trabajo futuro**: Ampliar el corpus a más canciones por artista, incorporar análisis de ritmo y estructura musical, aplicar modelos de lenguaje más avanzados (BERT en español)
- **Mejora potencial**: Incluir análisis diacrónico más granular (por año en lugar de por década)

## Autor
[Tu nombre] - [Tu email o GitHub]  
Trabajo Integrador - NLP - Diciembre 2023

---

*Nota: Este análisis forma parte del trabajo integrador de Procesamiento del Lenguaje Natural, explorando técnicas computacionales para el estudio literario-musical.*
