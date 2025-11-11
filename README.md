# Análisis de Señales Telefonicas

Este repositorio contiene un conjunto de notebooks para el analisis de las señales telefonicas.
La intensión es que sirva a modo de ejemplo para la cátedra Medidas Electrónicas I de la UTN FRBA.


### Notebooks
- **Analisis de fourier de señales telefonicas :** (`./notebooks/fft_analysis.ipynb`) Un analisis de fourier sobre los tonos telefonicos obtenidos, aplicando FFT y ventaneo.
- **Clasificacion por Redes Convolucionales :** (`./notebooks/convnet_classifier.ipynb`) Un ejemplo minimalista de la implementacion de redes neuronales convolucionales para la clasificacion de tonos telefónicos utilizando Pytorch.
- **Clasificacion por Redes Recurrentes (MAMBA) :** (`./notebooks/mamba_classifier.ipynb`) Un basico de redes recurrentes para la clasificación de tonos telefónicos. La red esta basada en blocques typo MAMBA (SSM) e implementado en Pytorch.
- **Conversion a TFLite (edge-inference) :** (`./notebooks/tflite_model_conversion.ipynb`) Este notebook muestra como convertir un model de Torch a TFLite, para poder ser usado en edge-inference. Esta hecho para soportar solo el modelo convolucional. Para la implementacion del mismo, referise [al ejemplo de Android](https://github.com/RawthiL/example_ndk_ml).

### Datos
Pulsos teléfonicos obtenidos con un osciloscopio Tektronix.
Para ejecutar los ejemplos, descomprimir el archivo `.zip` provisto dentro de la carpeta `./data`.

### Normas
La Norma Técnica CNC-St2-44.01 V02.1.1 (Argentina) que gobierna las carácteristicas de los aparatos telefónicos.