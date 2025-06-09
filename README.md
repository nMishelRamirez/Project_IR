# Sistema de Recuperación de Información: Gaming Corpus

Este proyecto implementa un sistema de recuperación de información sobre un corpus del dominio de videojuegos. Permite indexar documentos, ejecutar consultas en lenguaje natural utilizando modelos TF-IDF y BM25, y evaluar los resultados mediante métricas estándar.

## Estructura del proyecto

```
📁 /project_root
├── 📁 docs/                  # Documentación
│   └── pdf/                 # Archivo PDF
├── 📁 src/                   # Datos
│   ├── corpus.jsonl         # Corpus original
│   ├── queries.jsonl        # Consultas de prueba
│   ├── qrels.tsv            # Archivo ground truth (relevancia)
│   └── preprocessing.py     # Funciones de preprocesamiento
├── 📁 video presses/         # Archivos de videojuegos
│   └── video.mp4            # Video demostrativo
├── ProyectoIR.py            # Script principal
├── README.md                # Instrucciones del proyecto
└── .gitignore               # Archivos a ignorar en Git
```

## Funcionalidades Implementadas
1. Carga y procesamiento del corpus
- Lectura de documentos desde corpus.jsonl
- Procesamiento de texto

2. Carga y procesamiento de consultas (queries)
- Lectura desde queries.jsonl
- Preprocesamiento idéntico al corpus

3. Construcción de modelos de recuperación
- Vectorización del corpus con TF-IDF
- Construcción de índice BM25 

4. Ejecución de consultas
- Recuperación de documentos utilizando:
- Ranking de documentos ordenados por relevancia

5. Evaluación del sistema
- Evaluación de la precisión de los resultados

## Instalación

**Clona el repositorio:**
```bash
git clone https://github.com/nMishelRamirez/Project_IR.git
cd proyecto-ir
```

## Requisitos
Para ejecutar el proyecto, se necesitan los siguientes paquetes:
Python 3.8+
Bibliotecas:
- pandas, numpy
- scikit-learn
- nltk
- rank_bm25


## Integrantes
- Mishel Ramírez
- Danna Zaldumbide 