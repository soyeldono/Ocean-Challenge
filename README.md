# Datathon Gran Canaria 2021 | Ocean Challenge

Este repositorio presentaremos nuestro modelo para calsificar tipos de suelos y objetos en el fondo del oceano por parte del concurso de *Datathon Gran Canaria 2021*.

Equipo:

- Donovan Mosheh Ramirez Trejo
- Sandro Ormeño


## Tabla de contenido
1. [Introducción](#introduction)
2. [Fondo Marino](#sea_bottom)
    1. [Descargar y Ejectuar](#download_and_execute)
    2. [Modelo](#model_sea_bottom)
    3. [Resultados](#show_results)


## Introducción <a name="introduction"></a>

Dadas unas imagenes tomadas por un submarino la meta es consegur clasificar el *suelo* del oceano y los *objetos* que se muestran (ya sea algas, rocas, basura, etc...).
Para ello se va a hacer uso de tecnicas de clasificación de imagenes usando redes neuronales convolucionales.

## Fondo Marino <a name="sea_bottom"></a>

Este reto consiste en clasificar el tipo de suelo en el cual se encuentra el submarino, para ello se usarán las imagenes en la carpeta 'ocean_v2'. 

### Descargar y Ejecutar <a name="download_and_execute"></a>

1. Verifica que tengas instalado las librerías:
- [Pytorch (con cuda)](https://pytorch.org/)
- [numPy](https://numpy.org/install/)
- [matplotlib](https://matplotlib.org/stable/users/installing.html)
- [PIL](https://pillow.readthedocs.io/en/stable/installation.html)

2. Descarga la carpeta del google drive
```
a
``` 

3. Abrir y Ejecutar todas las celdas del notebook llamado 'sea_bottom.ipynb'
(Nota: Asegurate de descargar el dataset en la misma carpeta donde se encuentra el notebook 'sea_bottom.ipynb')

### Modelo <a name="model_sea_bottom"></a>

Para este problema se optó por usar la red neuronal pre-entranda 'ResNet50' para facilitar el aprendizaje de la red neuronal. Junto a la red se decidió usar el optimizador 'Adam' junto a la
funcion de error 'l1_loss'.


### Resultados <a name="show_results"></a>

Net Prediction / Real

![result](https://user-images.githubusercontent.com/38016639/133942791-914df2c6-930b-4be0-b01f-a7377afc7d6b.png)

