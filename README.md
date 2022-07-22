# Entendiendo-Machine-Learning-desde-Cero
Es es un espacio dedicado al entendimiento del Machine Learning desde cero.

Introducción
Esta guía servirá como introducción a los conceptos básicos de la API de Keras & TensorFlow.

📚 En esta guía, aprendemos sobre:

Tensores, variables y gradientes en TensorFlow
Creación de capas subclasificando la clase Layer
Escribir bucles de entrenamiento de bajo nivel
Seguimiento de las pérdidas creadas por las capas a través del método add_loss()
Seguimiento de las métricas en un bucle de entrenamiento de bajo nivel
Acelerar la ejecución con untf.function
Ejecución de capas en modo de entrenamiento o inferencia
La API funcional de Keras
También verás la API de Keras en acción en dos ejemplos de investigación de extremo a extremo: un Autocodificador Variacional y una Hypernetwork.


Tensores
TensorFlow es una capa de infraestructura para una programación diferenciable. En esencia, es un marco para manipular matrices N-dimensionales (tensores), al igual que NumPy.

Sin embargo, hay tres diferencias clave entre NumPy y TensorFlow:

TensorFlow puede aprovechar aceleradores de hardware como GPU y TPU.
TensorFlow puede calcular automáticamente el gradiente de expresiones tensor diferenciables arbitrarias.
El cálculo de TensorFlow se puede distribuir a un gran número de dispositivos en una sola máquina y a un gran número de máquinas (potencialmente con varios dispositivos cada una).
