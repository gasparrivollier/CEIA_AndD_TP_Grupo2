# 🗂️ CEIA_AndD_TP_Grupo2 | Análisis de Datos - Viajes de Taxi NYC 2024

Este proyecto contiene un análisis exploratorio y de procesamiento de
datos sobre los viajes de taxi amarillo de la ciudad de Nueva York
(Yellow Taxi Trips) durante el año 2024.\
Los datos se encuentran almacenados en formato **Parquet** y el análisis
principal se realiza en **Python** mediante Jupyter Notebooks.

------------------------------------------------------------------------

## 📁 Estructura del repositorio

    ├── bin/                          # Scripts o utilidades ejecutables (si aplica)
    │
    ├── dataset/                      # Datos fuente en formato .parquet
    │   ├── yellow_tripdata_2024-01.parquet
    │   ├── yellow_tripdata_2024-02.parquet
    │   ├── ...
    │   └── yellow_tripdata_2024-12.parquet
    │
    ├── notebooks/
    │   └── AndD_tp.ipynb             # Notebook principal con el análisis y visualización
    │
    └── README.md                     # Descripción general del proyecto

------------------------------------------------------------------------

## 🚀 Objetivo

Explorar, limpiar y analizar la evolución mensual de los viajes de taxi
en NYC durante el año 2024, utilizando técnicas de análisis de datos con
**pandas**, **matplotlib**, y **seaborn**, junto con la lectura
eficiente de archivos Parquet.

------------------------------------------------------------------------

## 🧩 Requisitos

Instalar las dependencias necesarias para ejecutar el análisis:

Python>3.10

**pip:**
``` bash
pip install -r requirements.txt
```
**uv:**

- Crear el venv
``` bash
uv venv --python 3.11
```
- Activar el venv
``` bash
.venv\Scripts\activate
```
- Instalar dependencias 

``` bash
uv sync
```

------------------------------------------------------------------------

## ▶️ Ejecución

1.  Abrir el notebook principal:

    ``` bash
    jupyter notebook notebooks/AndD_tp.ipynb
    ```

2.  Ejecutar las celdas paso a paso para reproducir el análisis.

------------------------------------------------------------------------

## 📊 Estructura de los datos

Cada archivo `.parquet` contiene los viajes de taxi de un mes específico
del año 2024, con columnas como:

-   `tpep_pickup_datetime` -- Fecha y hora de inicio del viaje\
-   `tpep_dropoff_datetime` -- Fecha y hora de finalización\
-   `passenger_count` -- Cantidad de pasajeros\
-   `trip_distance` -- Distancia del viaje en millas\
-   `fare_amount` -- Tarifa total del viaje\
-   `payment_type` -- Método de pago

------------------------------------------------------------------------

## Autores


