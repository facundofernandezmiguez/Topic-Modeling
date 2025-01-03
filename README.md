# Análisis de Tópicos en Conversaciones de Contact Center

## Descripción
Este proyecto implementa un análisis de modelado de tópicos sobre un corpus de transcripciones de llamadas de un contact center. El objetivo principal es identificar y analizar los temas predominantes en las conversaciones entre clientes y agentes.

## Dataset
- **Tamaño del corpus**: 640 transcripciones de llamadas
- **Contenido**: Conversaciones entre clientes y agentes de contact center
- **Ubicación**: Los datos de entrada se encuentran en la carpeta `corpus/`

## Metodología
El análisis se realiza utilizando el método de Latent Dirichlet Allocation (LDA), una técnica de modelado probabilístico que permite descubrir temas abstractos en una colección de documentos.

## Estructura del Proyecto
```
Topic-Modeling/
├── notebooks/           # Jupyter notebooks con el análisis
│   └── LDA_model.ipynb
├── output/             # Archivos generados
│   └── plot.png
├── corpus/             # Datos de entrada
├── requirements.txt    # Dependencias del proyecto
└── README.md
```

## Requisitos
Para instalar las dependencias necesarias:
```bash
pip install -r requirements.txt
```

Dependencias principales:
- Python 3.x
- pandas
- gensim
- nltk
- wordcloud
- pyLDAvis
- jupyter
- matplotlib

## Uso
1. Asegúrese de tener instaladas todas las dependencias necesarias
2. Abra el Jupyter Notebook en la carpeta `notebooks`
3. Ejecute las celdas en orden para realizar el análisis

## Resultados
El análisis permite identificar los tópicos más relevantes en las conversaciones del contact center, lo que puede ser útil para:
- Mejorar la calidad del servicio
- Identificar patrones comunes en las consultas
- Optimizar la capacitación de los agentes
