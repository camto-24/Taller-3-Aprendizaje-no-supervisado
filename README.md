# Talleres S5 y S6 — Sistemas de Recomendación
Este repositorio contiene el desarrollo de dos talleres prácticos del curso de Aprendizaje No Supervisado, enfocados en la construcción de sistemas de recomendación aplicados a datos reales.

## Objetivo general
Explorar y aplicar técnicas de sistemas de recomendación:
- Filtrado colaborativo usando datos de música (Last.fm)
- Filtrado basado en contenido usando textos (blog de Hernán Casciari)

### Caso 1: Recomendando Música (Last.fm)
Se construye un sistema de recomendación de música utilizando datos de usuarios y artistas de Last.fm, con el objetivo de entender patrones de consumo musical.

#### artists.dat
- id: identificador del artista
- name: nombre del artista
- url: enlace a Last.fm
- pictureURL: imagen del artista

#### user_artists.dat
- userID: identificador del usuario
- artistID: identificador del artista
- weight: número de reproducciones

### Caso 2: Recomendando el Blog de Hernán Casciari
Se construye un sistema de recomendación basado en contenido para sugerir cuentos del blog del escritor Hernán Casciari, utilizando técnicas de procesamiento de texto.


#### blog_casciari.csv
Contiene cuentos, títulos y contenido textual de los posts del blog.

### Resultados esperados
- Recomendación de artistas similares basada en comportamiento de usuarios
- Recomendación de cuentos similares basada en contenido textual
- Comprensión de sistemas de recomendación colaborativos y basados en contenido
