# Procesamiento de Imagenes para Diagnostico de Transformadores
Este proyecto analiza imágenes térmicas y visuales de transformadores para identificar zonas frías, medias y calientes, así como aisladores, líneas eléctricas y vegetación cercana. A partir de un archivo ZIP, el sistema procesa cada imagen y genera un diagnóstico automático apoyado en filtros, bordes y segmentación con K-Means.

# Estructura del repositorio

- ProyectoIV.ipynb → Notebook principal del análisis (Google Colab).

- README.md → Este archivo.

- /ProyectoIV.zip/ → Archivo subido por el usuario que contiene las imágenes a analizar.

El archivo ZIP contiene imágenes térmicas en formato visible (JPG). Cada imagen puede seleccionarse durante la ejecución del notebook.

# Requisitos del proyecto

El proyecto está diseñado para ejecutarse principalmente en Google Colab, aunque también puede funcionar en un entorno local.

Dependencias necesarias (si se ejecuta localmente):

- Python 3.8 o superior

- Librerías:

- numpy

- matplotlib

- pandas

- opencv-python

- scikit-learn

- scipy

- zipfile / os
