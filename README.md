# Visualización-de-Datos
Este proyecto se enfoca en el análisis y visualización de datos científicos obtenidos desde Scopus, con el objetivo de estudiar cómo los jóvenes universitarios utilizan la Inteligencia Artificial en distintos contextos sociales, académicos y creativos. El flujo de trabajo combina limpieza de datos, procesamiento semántico, análisis bibliométrico y visualización interactiva.

El análisis fue desarrollado principalmente en Python, utilizando estructuras de procesamiento de texto, clasificación temática y exploración de patrones semánticos dentro de artículos científicos. El proyecto parte de una metodología de segundo orden, donde los documentos científicos son tratados como datos analizables para identificar tendencias, relaciones conceptuales y clusters temáticos dentro de la producción académica.

Herramientas y librerías utilizadas
Limpieza y procesamiento de datos
- Pandas
Utilizado para cargar, limpiar, transformar y analizar archivos CSV provenientes de Scopus. Permitió trabajar con tablas de datos, eliminar inconsistencias y estructurar metadatos científicos. En el script principal se usa explícitamente para el análisis tabular de datos.
Biblioteca estándar de Python:
- re → limpieza mediante expresiones regulares.
- unicodedata → normalización de acentos y caracteres especiales.
- collections.Counter → conteo de términos y frecuencias.
- math.log → cálculo de métricas similares a TF-IDF.
- difflib.SequenceMatcher → comparación de similitud entre autores y términos.

# Análisis semántico y clasificación temática
El proyecto implementa diccionarios temáticos personalizados para detectar patrones relacionados con:

- IA generativa
- Educación superior
- Creatividad digital
- Interacción social
- Redes sociales
- Producción multimedia

# Los artículos son clasificados automáticamente en clusters como:

- Social
- Académico
- Creativo
- Mixto/Otros

Esto permite construir mapas semánticos y detectar relaciones entre conceptos dentro del corpus científico.

Visualización de datos

Para la visualización de resultados se utilizaron diferentes enfoques orientados al análisis exploratorio y representación interactiva de clusters bibliométricos:

Matplotlib

Generación de gráficos estadísticos y visualizaciones básicas.
Plotly

Creación de visualizaciones interactivas y exploración dinámica de datos.
PyVis

Construcción de redes semánticas y grafos interactivos entre conceptos, autores y clusters.
NetworkX

Modelado de redes complejas y relaciones entre nodos bibliométricos.
Matplotlib Maplotlib / Metraplant (visualización conceptual)

Utilizado como base para representar conexiones visuales entre categorías temáticas y relaciones conceptuales dentro del análisis.
¿Qué hace el proyecto?

# El sistema:

- Importa datos científicos desde Scopus.
- Limpia y normaliza los textos.
- Detecta términos relevantes relacionados con IA.
- Clasifica artículos por clusters temáticos.
- Extrae frecuencias y relaciones semánticas.
- Genera visualizaciones y mapas de interacción conceptual.
- Permite interpretar tendencias sobre el uso de IA en estudiantes universitarios.
- Concepto clave: Visualización de datos

La visualización de datos es el proceso de transformar información numérica o textual en representaciones gráficas comprensibles. Su objetivo es revelar patrones, tendencias y relaciones que serían difíciles de detectar únicamente leyendo tablas o documentos.

En este proyecto, la visualización permite:

- identificar conexiones entre conceptos;
- observar cómo se agrupan los artículos;
- detectar relaciones entre IA, educación y creatividad;
- construir mapas semánticos interactivos;
- interpretar dinámicas bibliométricas dentro del corpus científico.

En términos reales, la visualización actúa como una “traducción visual” del conocimiento científico, facilitando el análisis sociotécnico de la producción académica sobre Inteligencia Artificial y jóvenes universitarios.
