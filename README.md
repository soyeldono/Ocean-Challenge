# Datathon Gran Canaria 2021 | Ocean Challenge

Este repositorio presentaremos nuestro modelo para calsificar tipos de suelos y objetos en el fondo del oceano por parte del concurso de *Datathon Gran Canaria 2021*.

Equipo:

- Donovan Mosheh Ramirez Trejo
- Participante 2
- Participante 3
.
.
.

(insertar imagen de resultados finales aqui)

## Tabla de contenido
1. [Introducción](#introduction)
2. [Fondo Marino](#sea_bottom)
    1. [Resultados](#show_final_results)
    2. [Descargar y Ejectuar](#download_and_execute)
    3. [Desarrollo y Solución del problema](#dev_and_solution)
        1. [Procesamiento de Imagenes](#images)
        2. [Modelo](#model)
        3. [Resultados](#show_results)
3. [Clasificar Elementos](#ocean_chalenge)
    (pendiente)


## Introudcción <a name="introduction"></a>

Dadas unas imagenes tomadas por un submarino la meta es consegur clasificar el *suelo* del oceano y los *obejtos* que se muestran (ya sea algas, rocas, basura, etc...).
Para ello se va a hacer uso de tecnicas de clasificación de imagenes usando redes neuronales convolucionales.

## Fondo Marino <a name="sea_bottom"></a>

**Todos los archivos relacionados a este reto se encuentran en la carpeta 'sea bottom'**

Este reto consiste en clasificar el tipo de suelo en el cual se encuentra el submarino, para ello se usarán las imagenes en la carpeta 'ocean_v2'. 

### Resultados <a name="show_final_results"></a>

(poner imagen de resultados aqui)

### Descargar y Ejecutar <a name="download_and_execute"></a>

1. Verifica que tengas instalado las librerías:
- [Pytorch](https://pytorch.org/)
- [numPy](https://numpy.org/install/)
- [matplotlib](https://matplotlib.org/stable/users/installing.html)
- [PIL](https://pillow.readthedocs.io/en/stable/installation.html)

2. Descarga el repositorio y acceda a la carpeta 'sea bottom'
```
git clone https://github.com/soyeldono/Ocean-Challenge.git
cd "sea bottom"
``` 
