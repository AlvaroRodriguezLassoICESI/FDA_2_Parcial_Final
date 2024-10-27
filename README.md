# Fundamentos de Analitica 2 - Parcial Final
# Clasificación y Localización de Pingüinos y Tortugas

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo capaz de clasificar y localizar pingüinos o tortugas en imágenes. A partir de un conjunto de datos proporcionado, que incluye imágenes y sus anotaciones correspondientes, el modelo debe identificar qué animal aparece en la imagen (pingüino o tortuga) y determinar su ubicación precisa dentro de la misma.

## Estructura del Proyecto

1. **Datos**: Las imágenes y las anotaciones vienen incluidas en el conjunto de datos, el cual ha sido preprocesado para facilitar el entrenamiento del modelo.
   
2. **Modelo**: El modelo utiliza técnicas de visión por computadora para la clasificación y localización de los animales, empleando arquitecturas avanzadas de redes neuronales.
   
3. **Entrenamiento**: El conjunto de datos está dividido en entrenamiento y validación para evaluar el rendimiento del modelo. Se utilizan técnicas de aumento de datos y regularización para mejorar la generalización.

4. **Evaluación**: Se evaluará la precisión del modelo en dos tareas:
   - Clasificación: Identificación de si la imagen contiene un pingüino o una tortuga.
   - Localización: Detección de la ubicación exacta del animal en la imagen mediante bounding boxes.

## Requisitos

- Python 3.x
- TensorFlow / PyTorch
- OpenCV
- Otros paquetes necesarios (ver `requirements.txt`)

