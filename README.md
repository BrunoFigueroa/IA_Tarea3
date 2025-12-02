# IA_Tarea3
IA tarea 3


DEPENDENCIAS:

Necesitas tener tensorflow instalado, puedes utilizar la version de GPU, o de CPU, en mi caso se utilizo la de CPU (gpu incompatible)
pip install tensorflow
pip install tensorflow-cpu
pip install matplotlib

Para que funcione el archivo .ipynb, el dataset tiene que estar organizado de la siguiente forma:

./dataset/AnnualCrop
./dataset/Forest
./dataset/HerbaceousVegetation
./dataset/Residential
./dataset/SeaLake
./dataset_test <- agrega manualmente las imagenes que quieres utilizar para el test de comparacion final, en mi caso agregue 1500 imagenes, 300 de cada clase de forma aleatoria.

basicamente, crear una carpeta llamada Dataset, y poner las carpetas con las imagenes dentro, separadas por el nombre de clase.
