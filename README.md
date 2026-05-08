## Talleres S5 y S6 — Sistemas de Recomendación
Este repositorio contiene el desarrollo de dos talleres prácticos del curso de Aprendizaje No Supervisado, enfocados en la construcción de sistemas de recomendación aplicados a datos reales.

# Objetivo general
Explorar y aplicar técnicas de sistemas de recomendación:
- Filtrado colaborativo usando datos de música (Last.fm)
- Filtrado basado en contenido usando textos (blog de Hernán Casciari)

### Caso 1: Recomendando Música (Last.fm)
Descripción

Se construye un sistema de recomendación de música utilizando datos de usuarios y artistas de Last.fm, con el objetivo de entender patrones de consumo musical.

Datos utilizados
artists.dat
id: identificador del artista
name: nombre del artista
url: enlace a Last.fm
pictureURL: imagen del artista
user_artists.dat
userID: identificador del usuario
artistID: identificador del artista
weight: número de reproducciones
Procesamiento de datos
Selección de variables relevantes
Renombramiento de columnas para facilitar la unión de bases
Unión de datasets mediante artistID
Limpieza y estructuración de los datos
Enfoque del modelo
Sistema de recomendación basado en interacción usuario–artista
Uso de similitud coseno para medir afinidad
Identificación de patrones de consumo musical
Caso 2: Recomendando el Blog de Hernán Casciari
Descripción

Se construye un sistema de recomendación basado en contenido para sugerir cuentos del blog del escritor Hernán Casciari, utilizando técnicas de procesamiento de texto.

Datos utilizados
blog_casciari.csv

Contiene cuentos, títulos y contenido textual de los posts del blog.

Procesamiento de texto
Limpieza del texto:
Eliminación de signos de puntuación
Conversión a minúsculas
Eliminación de acentos
Eliminación de stopwords
Vectorización del texto usando TF-IDF
Cálculo de similitud entre documentos
Enfoque del modelo
Sistema de recomendación basado en contenido
Representación vectorial de documentos
Medición de similitud coseno entre cuentos
Recomendación de textos similares
Tecnologías utilizadas
Python
Pandas
NumPy
Scikit-learn
Apyori
Matplotlib
Procesamiento de lenguaje natural (TF-IDF)
Estructura del repositorio
📦 repo
 ┣ 📂 data
 ┃ ┣ artists.dat
 ┃ ┣ user_artists.dat
 ┃ ┗ blog_casciari.csv
 ┣ S5_recomendacion_musica.ipynb
 ┣ S6_recomendacion_blog.ipynb
 ┗ README.md
Resultados esperados
Recomendación de artistas similares basada en comportamiento de usuarios
Recomendación de cuentos similares basada en contenido textual
Comprensión de sistemas de recomendación colaborativos y basados en contenido
Autor

Proyecto desarrollado como parte del curso de Aprendizaje No Supervisado con fines académicos.
