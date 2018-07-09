# IIC3697_RNet
Implementación de R-Net en Python 3.6 con Keras 2.0.6

### Instrucciones de replicación:

* Descargar data preprocesada (carpeta data): https://drive.google.com/drive/folders/19ojMzFgfADbifPdLVwnfgqVaKJqDT9bR?usp=sharing 

* Una vez descargada la data, entrenar desde el notebook 

* Para predicciones, se debe descargar el script de prediccion desde el repositorio del cual basamos nuestra implementacion: https://github.com/YerevaNN/R-NET-in-Keras

### Contenido del repositorio: 

* En la carpeta predictions pueden encontrar las prediciones para el dataset de dev_1.1 para cada modelo que fue persistido. Además pueden encontrar 2 script, uno para generar las predicciones dado los archivos de modelo, y un script que calcula tanto el f1 como el exact_match

* En la carpeta modelo, pueden encontrar todos nuestros modelos persistidos con su respectivo valor de loss y de la iteracion que genero dicho modelo.

Por ultimo, como requerimiento estricto se necesita la versión 2.0.6 de keras.
