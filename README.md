PREDICCION DE LA DESERCIÓN DE CLIENTES EN UN BANCO 

1. DESCRIPCIÓN DEL PROYECTO: 
El principal objetivo de este proyecto, es desarrollar un modelo de Machine Learning para predecir la deserción de clientes de un banco. 

2. CONJUNTO DE DATOS:
El conjunto de datos consta de 10.000 registros de clientes, además de varias columnas. Estas incluyen información de la cuenta del cliente como servicios regisdtrados, datos demográficos, nombre, entre otros.

3. Preprocesamiento de datos y desarrollo del modelo
Ambos procesos se realizaron en Phyton, Google Colab. Se utilizan varias bibliotecas, entre ellas:
import pandas as pd
import matplotlib as plt
import seaborn as sns
import os
import numpy as np
import math as mat

4. Modelos:
Se probaron cinco modelos diferentes de Machine Learning para predecir la rotación de clientes en un banco, incluyendo Árbol de Decisión, Random Forest Classifier, Support Vector Classifier, Clasificador de Perceptrón Multicapa y Clasificador XGBoost.
Finalmente, utilicé los modelos Random Forest y XGBoost en la aplicación final. Estos modelos demostraron tener un rendimiento superior en las pruebas y fueron los más efectivos para predecir la deserción de clientes.



