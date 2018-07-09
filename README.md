# IIC3697_RNet
Implementación de R-Net en Python 3.6 con Keras 2.0.6

### Instrucciones de replicación:

* Descargar data preprocesada (carpeta data): https://drive.google.com/drive/folders/19ojMzFgfADbifPdLVwnfgqVaKJqDT9bR?usp=sharing 

* Una vez descargada la data, entrenar desde el notebook 

* Para predicciones, se debe descargar el script de predicción desde el repositorio del cual basamos nuestra implementacion: https://github.com/YerevaNN/R-NET-in-Keras

### Contenido del repositorio: 

* En la carpeta predictions pueden encontrar las prediciones para el dataset de dev_1.1 para cada modelo. Además, en esta carpeta  pueden encontrar 2 scripts, uno para generar las predicciones dado los archivos de modelo (`pred.sh`), y un script que calcula tanto el f1 como el exact_match (`script_eval.sh`).

* En la carpeta modelo, se guardarán snapshots del modelo después de cada época de entrenaiento. El nombre del archivo cointiene el valor de pérdida para el entrenamiento y evaluadión y el número de la época que lo generó: `<Epoch Number>_t<Training Loss>_v<Validation Loss>.model`. El archivo de la iteración 41 de R-Net está en el repositorio.

Por ultimo, como requerimiento estricto, se necesita la versión 2.0.6 de Keras.
