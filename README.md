# Tarea: Analytics on GeoDataFrames - COVID-19 ☣️

Alumnos:
* Nicolas Silva Andujar
* Rosa Huamaní Pucho

---------------------------------------------------------------------------

Esta tarea consiste en la elaboración de mapas correspondientes al número de contagiados y fallecidos por COVID-19 durante el 2021, utilizando el método de Correlación Local Espacial. Esto se realiza para encontrar clusters espaciales y valores atípicos espaciales.

---------------------------------------

### **Contenido de la data** 📈

______________

### **Diccionario de datos** 📍

| **Variable**     | **Tipo**     | **Denominación**                            | **Valores**                               |
|--------------|----------|-----------------------------------------|---------------------------------------|
|   CATEGORÍA   | object | Categoría entre fallecido y contagiado                |            "FALLECIDO", "CONTAGIADO"                           |
|   SEXO   | object | Sexo del individuo                |              "MASCULINO", "FEMENINO"                         |
|   EDAD   | float64 | Edad del individuo                 |                                       |
|    PROVINCIA_x   | object | Provincia del caso reportado                                |                               |
|   DEPARTAMENTO   | object | Departamento del caso reportado                 |                                       |
|   year_2020   | object | Año 2020                |                                       |
|   year_2021   | object | Año 2021                 |                                       |
|   year_2022   | object | Año 2022                 |                                       |
|   year_2023  | object | Año 2023                 |                                       |
|   year_2024   | object | Año 2024                 |                                       |

__________

### **Leyenda** 🧭🗺️

|**Nombre**| **Elemento**                  | **Descripción**                                                                                                                         |
|----------------|---------------------------|------------------------------------------------------------------------------|------------------------------------------------------|
| 1 hotSpot| **Relleno rojo** 🟥         |Polígono donde los valores de la variable de análisis (sea contagios o fallecidos) tiene valores altos y se encuentra rodeada de polígonos con valores que también son elevados.  |
| 2 coldOutlier| **Relleno verde**🟩           | Polígono donde los valores de la variable de análisis son bajos pero se encuentra rodeada de polígonos con valores elevados  |
| 3 coldSpot| **Relleno negro**⬛ | Polígono donde los valores de la variable de análisis son bajos y se encuentra rodeada de polígonos con valores altos |
| 4 hotOutlier| **Relleno naranja**🟧    | Polígonos donde los valores de la variable de análisis son altos pero se encuentra rodeada de polígonos con valores bajos                                                                      |
