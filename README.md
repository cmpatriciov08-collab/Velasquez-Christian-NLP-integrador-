Análisis de NLP: Evolución Lírica en el Rock Argentino
Descripción
Este análisis explora la evolución lírica en la obra solista de tres figuras clave del rock argentino: Charly García, Luis Alberto Spinetta y Fito Páez, abarcando el período de 1980 a 2009. El corpus, compuesto por 24 letras de canciones, fue recolectado mediante web scraping y preprocesado para su análisis computacional. Los objetivos principales fueron cuantificar diferencias en el vocabulario y la complejidad entre artistas, identificar patrones de evolución a lo largo del tiempo y comparar la efectividad de diferentes técnicas de NLP para este tipo de texto. Los hallazgos revelaron diferencias estilísticas medibles entre los artistas, una evolución gramatical y léxica a nivel del corpus general a lo largo de las décadas, y la superioridad de los Word Embeddings para capturar similitud semántica en letras de canciones.

Información del Corpus
Tipo: Música (Rock Argentino)
Tamaño: 24 textos, aproximadamente 4162 palabras totales (lemas sin stop words)
Fuentes principales: Rock.com.ar
Período temporal: 1980-2009
Criterios de selección: Letras de canciones de álbumes solistas de Charly García, Luis Alberto Spinetta y Fito Páez publicados entre 1980 y 2009, con 8 canciones por artista.
Técnicas de NLP Aplicadas
Preprocesamiento de texto (limpieza, tokenización, stop words)
Análisis con Bag of Words (BoW) y TF-IDF
Análisis con Word Embeddings (spaCy)
[Técnica complementaria aplicada: POS/Sentiment/NER]
Principales Hallazgos
[Hallazgo más importante #1] Diferencias cuantificables en el uso de sustantivos, verbos y adjetivos entre los artistas, sugiriendo estilos líricos distintos (Charly: más verbos, Fito: más sustantivos, Spinetta: ligeramente más adjetivos).
[Hallazgo más importante #2] Tendencia evolutiva en el corpus general hacia un lenguaje más descriptivo y conceptual en las décadas posteriores (aumento de sustantivos y adjetivos, ligera disminución de verbos).
[Hallazgo más importante #3] Los Word Embeddings identificaron similitud semántica entre canciones que no compartían vocabulario explícito, revelando afinidades temáticas y conceptuales profundas.
[Comparación entre métodos: cuál funcionó mejor y por qué] Los Word Embeddings fueron más útiles para capturar similitud semántica y conceptual en letras de canciones, alineándose mejor con la percepción intuitiva del estilo lírico, mientras que BoW/TF-IDF fue efectivo para el análisis de frecuencia y vocabulario explícito.
Tecnologías Utilizadas
Python 3.x
pandas, numpy
scikit-learn
spaCy
matplotlib, seaborn
nltk
wordcloud
Instrucciones de Reproducción
Clonar este repositorio (si aplica, o asegurar acceso al notebook y archivos).
Instalar dependencias: pip install pandas numpy scikit-learn spacy matplotlib seaborn nltk wordcloud -q
Descargar modelo spaCy: python -m spacy download es_core_news_md -q
Descargar recursos NLTK: import nltk; nltk.download('stopwords'); nltk.download('punkt')
Ejecutar el notebook secuencialmente en un entorno como Google Colab.
Limitaciones y Trabajo Futuro
[Principal limitación encontrada] El tamaño del corpus limita la generalización y el análisis de aspectos más finos como figuras retóricas o sintaxis compleja.
[Qué análisis te gustaría hacer en el futuro] Modelado de temas (LDA), análisis de sentimiento/emoción, análisis sintáctico detallado y comparación con otros géneros/artistas.
Autor
[Tu nombre] - [Tu email o GitHub] Trabajo Integrador - NLP - [Fecha]

---

*Nota: Este análisis forma parte del trabajo integrador de Procesamiento del Lenguaje Natural, explorando técnicas computacionales para el estudio literario-musical.*
