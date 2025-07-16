# Minería de Texto (NLP)

**Universidad del Desarrollo**  
**Curso:** Minería de Texto  
**Profesor:** María Raveau  
**Fecha de entrega:** 20 de julio de 2025, 23:59  
**Autor:** Camilo Rivera  

## Descripción

Este proyecto aborda la extracción de contenido útil a partir de los textos de los **cabildos provinciales de 2016**, en el contexto de una solicitud hipotética realizada por una agencia gubernamental interesada en conocer las opiniones de los participantes.

A partir de los textos de fundamento, se realiza un análisis exploratorio y visual de conceptos clave mediante procesamiento de lenguaje natural (NLP), con el objetivo de describir con mayor claridad los temas tratados por los ciudadanos en los cabildos.

## Objetivos de la tarea

1. **Selección de un concepto** con suficientes menciones dentro del dataset de cabildos provinciales.
2. **Preprocesamiento de texto**, incluyendo tokenización, eliminación de stopwords y lematización.
3. Generación de:
   - WordCloud de **tokens sustantivos**.
   - WordCloud de **bigramas sustantivo-adjetivo**.
4. Creación de una **red de bigramas sustantivo-adjetivo**.
5. Redacción de una **descripción cualitativa** del concepto seleccionado, apoyándose en frases de ejemplo y las visualizaciones generadas.

## Estructura del repositorio

📁 mineria_de_texto_NLP/
├── tarea1_camilo_rivera.ipynb # Código comentado en Jupyter Notebook
├── data/
│ └── resultadocabildoprovincial.xlsx # Dataset de los cabildos (visto en clases)
├── outputs/
│ ├── wordcloud_tokens.png
│ ├── wordcloud_bigramas.png
│ └── red_bigramas.png
└── README.md


## Librerías utilizadas

- `pandas`: manipulación de datos tabulares.
- `nltk`: tokenización, stopwords y bigramas.
- `stanza`: lematización y análisis gramatical.
- `matplotlib`, `wordcloud`: visualización de nubes de palabras.
- `networkx`: construcción y visualización de la red de bigramas.

> **Nota:** En caso de utilizar código o funciones externas, se incluyen referencias y explicaciones en el notebook.

## Consideraciones

- El concepto fue escogido cuidadosamente para asegurar una cantidad suficiente de datos para el análisis.
- Se presta especial atención a la limpieza de texto y selección gramatical (solo sustantivos y adjetivos).
- Las visualizaciones son clave para apoyar la interpretación y descripción del concepto.

---

