# Tarea: Analytics on GeoDataFrames - COVID-19 ☣️

Alumnos:
* Nicolas Silva Andujar
* Rosa Huamaní Pucho

---------------------------------------------------------------------------

Esta tarea consiste en la elaboración de mapas correspondientes al número de contagiados y fallecidos por COVID-19 durante el 2021, utilizando el método de Correlación Local Espacial. Esto se realiza para encontrar clusters espaciales y valores atípicos espaciales.

---------------------------------------

### **Diccionario de datos** 📍

| **Variable**     | **Tipo**     | **Denominación**                            | **Valores**                               |
|--------------|----------|-----------------------------------------|---------------------------------------|
|   CATEGORÍA   | object | Categoría entre fallecido y contagiado                |            "FALLECIDO", "CONTAGIADO"                           |
|   SEXO   | object | Sexo del individuo                |              "MASCULINO", "FEMENINO"                         |
|   EDAD   | float64 | Edad del individuo                 |                                       |
|    PROVINCIA_x   | object | Provincia del caso reportado                                |                               |
|   DEPARTAMENTO   | object | Departamento del caso reportado                 |                                       |
|   year_2020   | object | Proporción de fallecidos y contagiados para el 2020                |                                       |
|   year_2021   | object | Proporción de fallecidos y contagiados para el 2021                  |                                       |
|   year_2022   | object | Proporción de fallecidos y contagiados para el 2022                 |                                       |
|   year_2023  | object | Proporción de fallecidos y contagiados para el 2023                  |                                       |
|   year_2024   | object | Proporción de fallecidos y contagiados para el 2024                |                                       |

__________

### **Leyenda** 🧭🗺️

| Nombre        | Elemento         | Descripción                                                                                                                              |
|---------------|------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| 1. hotSpot    | Relleno rojo 🟥   | Polígono donde los valores de la variable de análisis (sea contagios o fallecidos) son **altos** y se encuentra rodeado de polígonos con valores también **elevados**. |
| 2. coldOutlier| Relleno verde 🟩 | Polígono donde los valores de la variable de análisis son **bajos**, pero está rodeado de polígonos con valores **elevados**.                    |
| 3. coldSpot   | Relleno negro ⬛ | Polígono donde los valores de la variable de análisis son **bajos** y está rodeado de polígonos con valores también **bajos**.                   |
| 4. hotOutlier | Relleno naranja 🟧 | Polígono donde los valores de la variable de análisis son **altos**, pero está rodeado de polígonos con valores **bajos**.                       |

Mapa para fallecidos 
---
![output](https://github.com/user-attachments/assets/2469a998-192f-47d7-ae1a-b1ceaa4ed093)

Mapa para contagiados
---
![2](https://github.com/user-attachments/assets/3966ab2e-e7d9-48e7-a74e-140489351120)

___

**Enlace a la tarea**😺: [https://nicosil02.github.io/Redes2/geoDF_ANALYTICS.html](https://nicosil02.github.io/Redes2/tareaoficial.html)



