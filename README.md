# Procesamiento Digital de Imágenes para Clasificación General de Imágenes: Proyecto Final

### Isaac Menchaca Panecatl

### Dr. Ulises Moya

### Maestría en Ciencias de la Computación

**Basado en el artículo**: [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/abs/1905.11946)  (2019), de Mingxing Tan y Quoc V. Le, que introduce un enfoque innovador para escalar redes neuronales convolucionales (CNNs) de manera eficiente y efectiva.

**Objetivo**: Desarrollar un sistema de clasificación de imágenes utilizando el modelo preentrenado EfficientNet-B0, evaluando el impacto de diversas técnicas de procesamiento digital de imágenes (desenfoque y ruido) en el rendimiento del modelo al clasificar 100 imágenes generales de un conjunto de datos seleccionado.

**Metodología**:


1.   Preparación de datos: Seleccionar 100 imágenes de un conjunto de datos de propósito general.
Realizar preprocesamiento para estandarizar el tamaño de entrada al modelo EfficientNet-B0.
2.   Clasificación base: Usar el modelo EfficientNet-B0 preentrenado para clasificar las imágenes originales y registrar las métricas.
1.   Pruebas con procesamiento de imágenes:
  - Desenfoque: Aplicar un filtro de desenfoque (Desenfoque Gaussiano) a las imágenes y realizar la clasificación usando EfficientNet-B0.
  - Ruido: Añadir ruido aleatorio (sal y pimienta) a las imágenes y repetir la clasificación.
2.   Análisis de resultados: Comparar las métricas de clasificación entre las imágenes originales y procesadas. Evaluar cómo cada técnica de procesamiento de imágenes influye en el rendimiento del modelo.
1.   Conclusiones: Identificar qué modificaciones de las imágenes afectan de manera positiva o negativa la precisión de la clasificación.
