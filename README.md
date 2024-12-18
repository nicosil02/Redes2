# Tarea: Analytics on GeoDataFrames - COVID-19 ☣️

Alumnos:
* Nicolas Silva Andujar
* Rosa Huamaní Pucho

---------------------------------------------------------------------------

Este repositorio consiste en la elaboración de mapas correspondientes al número de contagiados y fallecidos por COVID-19 durante el 2021, utilizando el método de Correlación Local Espacial. Esto se realiza para encontrar clusters espaciales y valores atípicos espaciales.

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
![f2](https://github.com/user-attachments/assets/70ef8901-2f30-493f-a15f-9b3441762743)

Mapa para contagiados
---
![c2](https://github.com/user-attachments/assets/a5a8715a-fdaa-4119-b3bc-7264391dcc0d)

___

**Enlace a la tarea**😺: [https://nicosil02.github.io/Redes2/geoDF_ANALYTICS.html](https://nicosil02.github.io/Redes2/tareaoficial.html)



