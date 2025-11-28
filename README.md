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

  numpy

  matplotlib

  pandas

  opencv-python

  scikit-learn

  scipy

  zipfile / os

# Ejecución del código en Google Colab

1. Abre el archivo ProyectoIV.ipynb en Google Colab.

2. Conéctate al entorno de ejecución (botón Conectar en la esquina superior derecha).

3. Ejecuta las celdas de arriba hacia abajo (o usa Runtime → Ejecutar todo).

4. Cuando el notebook lo indique, sube el archivo ProyectoIV.zip, que debe contener tus imágenes.

6. El sistema listará las imágenes disponibles y te pedirá seleccionar una.

Una vez elegida, se realizará automáticamente:

   - Preprocesamiento

   - Análisis térmico

   - Segmentación K-Means

   - Detección de objetos

   - Generación de tablas y gráficos

7. Al finalizar, se mostrarán:

   - Diagnóstico térmico

   - Tablas de fallas

   - Resultados del clustering

   - Matriz de confusión

   - Imágenes procesadas (bordes, detecciones, zonas térmicas)

   - Vistas comparativas de las capas generadas

El notebook incluye también explicaciones paso a paso para facilitar la interpretación.

# Formato esperado de los datos

El archivo ProyectoIV.zip debe contener únicamente imágenes en formato .jpg (JPEG).

Las imágenes deben mostrar transformadores eléctricos o zonas térmicas relevantes.
No hay restricciones adicionales.

# Conclusiones

El sistema permite analizar imágenes térmicas y visuales de transformadores para identificar patrones relevantes como zonas frías, medias y calientes, así como posibles riesgos asociados a ensuciamiento, daños físicos o sobrecalentamientos.
El proceso automatizado facilita una evaluación rápida del estado del equipo y apoya la toma de decisiones en mantenimiento preventivo.
