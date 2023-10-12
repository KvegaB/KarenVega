# Modelo de Ising con algoritmo metropolis

Se presenta en un notebook de jupyter en el lenguaje Python que permite simular el modelo de Ising para una red cuadrada con condiciones periodicas.

## Descripción

Para una red de espines con una orientación hacia arriba (+1) y (-1) en una orientación hacia el modelo de Ising 2D permite análizar la transición de fase de magnetización de este sistema al variar la temperatura.

## Información relevante
- Se uso Python 3.10.11 
  ### Librerias
  - import random
  - import math
  - import copy
  - import numpy as np
  - from matplotlib.colors import ListedColormap
  - import matplotlib.pyplot as plt
## Parámetros
  - Tamaño de la Red N = 20
  - Números de pasos t = 60000
  - Constante de Boltzmann kb=1
  - Constante de integral de intercambio J = 1
  - Rango de temperaturas N_tem = 30
    (15 temperaturas antes y después de Tc=2.7)
    -Tiempo de compilación 35min
El código adjunto de modelo de Ising tiene como parámetros iniciales una red de espines aleatorios. sin embargo, puede se puede variar la cantidad de espines hacia arriba y hacia abajo, respecto a esto se hizo el análisis.  Realizado para 60mil pasos y 15 temperaturas antes y después de la temperatura critica Tc.
