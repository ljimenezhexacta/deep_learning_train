# Deep Learning

## Redes Neuronales

| Capítulo | Descripción | Herramientas |
|------|-------------|--------------|
| 1. Introducción a las Redes Neuronales Artificiales | En este capítulo se explorarán las redes neuronales artificiales, que son modelos inspirados en el cerebro humano para el procesamiento de información. Aprenderás los conceptos básicos de las redes neuronales, su estructura y funcionamiento, y cómo se utilizan en el campo del aprendizaje profundo. | - |
| 2. Herramientas para el Desarrollo de Redes Neuronales | En este capítulo se presentarán las herramientas más comunes utilizadas en el desarrollo de redes neuronales. Se abordarán temas como la API Keras, que proporciona una interfaz de alto nivel para la construcción de redes neuronales, y los backends populares como TensorFlow, Theano y CNTK. También se discutirán las bibliotecas de bajo nivel como CuDA, cuDNN, BLAS y Eigen, así como las opciones de hardware como GPU y CPU. | Keras, TensorFlow, Theano, CNTK, CuDA, cuDNN, BLAS, Eigen, GPU, CPU |
| 3. Introducción al Deep Learning | En este capítulo se introducirá el concepto de deep learning y su relación con la inteligencia artificial y el machine learning. Se explicarán las diferencias entre estos tres términos y se explorarán las ventajas y aplicaciones del deep learning en diversas áreas. | - |
| 4. Comparación entre el Machine Learning Tradicional y el Deep Learning | En esta capítulo se compararán los enfoques del machine learning tradicional y el deep learning. Se analizará el flujo de trabajo típico en ambos enfoques, desde la ingeniería de características hasta la clasificación de datos, destacando cómo el deep learning integra el aprendizaje de características y la clasificación en una sola etapa. | - |
| 5. Problemas Comunes en Deep Learning | En este capítulo se abordarán dos problemas comunes en el deep learning: el overfitting (sobreajuste) y la caja negra. Se explicará qué es el overfitting y cómo evitarlo, así como las limitaciones de interpretación de las redes neuronales como cajas negras. | - |
| 6. Construyendo tu Primera Red Neuronal con Keras | En esta capítulo se guiará al estudiante a través del proceso de construcción de su primera red neuronal utilizando la biblioteca Keras. Se explicará cómo cargar y preprocesar conjuntos de datos, construir una arquitectura de red neuronal básica, compilar el modelo y ajustar los datos. Se utilizará el ejemplo de reconocimiento de dígitos utilizando el conjunto de datos MNIST. | Keras, numpy, matplotlib.pyplot |
| 7. Entrenando y Evaluando el Modelo de tu Red Neuronal | En este capítulo se enseñará cómo entrenar y evaluar el modelo de una red neuronal utilizando los datos de entrenamiento y prueba. Se explicará cómo ajustar los datos de entrada, entrenar el modelo con los datos de entrenamiento, y evaluar la precisión del modelo utilizando los datos de prueba. | - |
| 8. La Neurona: La Unidad Básica de una Red Neuronal | En este capítulo se profundizará en el concepto de la neurona, que es la unidad básica de una red neuronal. Aquí se explorará en detalle la estructura y el funcionamiento de una neurona artificial en una red neuronal. Se abordarán conceptos como las entradas, los pesos, las sumas ponderadas, las funciones de activación y las salidas de una neurona. Se explicará cómo se realiza el cálculo de una neurona y cómo contribuye a la predicción final del modelo. | - |
| 9. Ejemplo Práctico: Compuertas Lógicas con Perceptrones | En este ejemplo práctico se mostrará cómo los perceptrones, una forma básica de redes neuronales, pueden resolver problemas simples de lógica booleana. Se utilizarán las compuertas AND, OR y XOR para ilustrar las capacidades y limitaciones de los perceptrones. | - |
| 10. Arquitectura de una Red Neuronal | En este capítulo se explorará la arquitectura general de una red neuronal. Se discutirán los conceptos de capa de entrada, capas ocultas y capa de salida, así como las características generales y específicas de cada una. Se explicará cómo las redes neuronales están compuestas por matrices y vectores, y cómo se realiza el producto matricial y se aplica el sesgo (bias). | - |
| 11. Funciones de Activación en las Redes Neuronales | Aquí se estudiarán las funciones de activación utilizadas en las redes neuronales. Se presentarán diferentes tipos de funciones, incluyendo las discretas y las continuas, como la función escalón, la función signo, la función sigmoidal, la función tangente hiperbólica, la función lineal rectificada (ReLU) y la función softmax. Se explicará el propósito y la aplicabilidad de cada función en el contexto de una red neuronal. | - |
| 12. Función de Pérdida en el Entrenamiento de Redes Neuronales | En este capítulo se abordará la función de pérdida, que es utilizada en el entrenamiento de redes neuronales para evaluar la discrepancia entre las predicciones del modelo y los valores reales. Se explorarán dos funciones de pérdida comunes: el error cuadrático medio (MSE) y la entropía cruzada (cross-entropy). Se explicará cómo se calculan y su relevancia en diferentes tareas de aprendizaje. | - |
| 13. Descenso del Gradiente: Optimizando los Pesos de la Red Neuronal | Aquí se introducirá el concepto de descenso del gradiente, que es un algoritmo utilizado para optimizar los pesos de una red neuronal y encontrar los mínimos de la función de pérdida. Se discutirá la importancia del learning rate y el momentum en el proceso de optimización, y cómo afectan la convergencia y la eficiencia del modelo. | - |
| 14. Backpropagation: Distribución del Error en la Red Neuronal | En este capítulo se explicará el algoritmo de backpropagation, que es utilizado para distribuir el error de pérdida en una red neuronal y ajustar los pesos de manera adecuada. Se discutirá cómo se propagan los errores desde la capa de salida hasta las capas ocultas y la capa de entrada, utilizando derivadas parciales y la regla de la cadena. Se mostrará cómo se actualizan los pesos de manera iterativa para minimizar la función de pérdida y mejorar el rendimiento del modelo. | - |


## Redes Neuronales con Python

| Capítulo | Descripción | Herramientas |
|---|---|---|
| 1. Dimensiones y Estructura de los Datos | En este capítulo entenderemos las dimensiones de los datos en Aprendizaje Profundo. Desde escalares hasta tensores, exploraremos cómo se representan diferentes tipos de datos y cómo influyen en el diseño de modelos. Veremos ejemplos prácticos de matrices y tensores en imágenes y series de tiempo. | Python, numpy |
| 2. Preparación de los Datos | La calidad de los datos es crucial en el Aprendizaje Profundo. En este capítulo aprenderás técnicas para limpiar, normalizar y transformar los datos antes de alimentarlos a una red neuronal. Veremos cómo manejar valores faltantes, codificar variables categóricas y dividir conjuntos de datos en entrenamiento y prueba. | Python, numpy |
| 3. Construyendo una Red Neuronal desde Cero | En este capítulo te sumergirás en la implementación de una red neuronal utilizando solo numpy y matemáticas. Desde la inicialización de parámetros hasta el entrenamiento y la predicción, conocerás cada paso del proceso. Analizaremos funciones de activación, función de pérdida y descenso del gradiente. | Python, numpy |
| 4. Entrenamiento y Evaluación del Modelo | En este capítulo aprenderás a entrenar y evaluar tu modelo de Aprendizaje Profundo. Exploraremos el proceso de propagación hacia adelante, cálculo del error, retropropagación y actualización de los parámetros. Veremos cómo ajustar hiperparámetros como el learning rate y las épocas para obtener mejores resultados. | Python, numpy |
| 5. Optimización y Regularización | La optimización y regularización son técnicas clave para mejorar el rendimiento de los modelos de Aprendizaje Profundo. En este capítulo aprenderás sobre optimizadores como el descenso del gradiente estocástico y la regularización L1 y L2. Veremos cómo prevenir el sobreajuste y mejorar la generalización del modelo. | Python, numpy |