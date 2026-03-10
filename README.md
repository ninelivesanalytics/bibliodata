# bibliodata
MVP para construir un grafo de libros enriquecido con “moods” (PLN) a partir de metadatos y descripciones. Incluye ingesta y limpieza de datos, modelado de BBDD en MySQL, modelado en grafo, cálculo de moods (léxico + sentimiento + semisupervisado) y una demo para consultas y recomendaciones.

## Primer paso (obligatorio): crear la estructura de carpetas

Antes de empezar a trabajar con el proyecto, **hay que crear la estructura base del repositorio** ejecutando el notebook de setup.

1. Abre y ejecuta (Run All) el notebook:
   - `notebooks/00_setup/00_create_structure.ipynb`

2. Esto creará las carpetas necesarias (`data/`, `src/`, `sql/`, `graph/`, `docs/`, etc.) y añadirá archivos `.gitkeep` para poder versionar la estructura.

> Nota: Git no trackea directorios vacíos. Por eso el notebook crea `.gitkeep` en algunas carpetas.