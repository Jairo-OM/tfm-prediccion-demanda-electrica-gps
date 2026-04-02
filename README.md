# Predicción de demanda eléctrica diaria en Santa Cruz (Galápagos)

Este repositorio contiene el desarrollo del Trabajo de Fin de Máster (TFM) orientado a la predicción de la demanda eléctrica diaria en el sistema de distribución de Santa Cruz (Puerto Ayora, Galápagos), utilizando modelos de series temporales, machine learning y deep learning.

## Objetivo del proyecto

Desarrollar y comparar distintos enfoques de modelado predictivo a partir de información histórica de consumo eléctrico, variables meteorológicas y variables de calendario, con el fin de identificar el modelo con mejor desempeño para la predicción de demanda eléctrica diaria.

## Estructura del repositorio

- `notebooks/`: notebooks del análisis, preparación de datos y modelado.
- `data/raw/`: dataset original utilizado en el estudio.
- `data/processed/`: datasets procesados generados por los notebooks.
- `outputs/tablas/`: tablas exportadas durante el análisis.
- `outputs/figuras/`: figuras generadas por los modelos y análisis exploratorio.

## Notebooks incluidos

1. `01_data_auditoria_y_preparacion.ipynb`
2. `02_eda_analisis_demanda.ipynb`
3. `03_analisis_serie_tiempo.ipynb`
4. `04_modelos_arima_sarimax.ipynb`
5. `05_modelos_ml.ipynb`
6. `06_modelos_lstm.ipynb`
7. `07_modelo_prophet.ipynb`

## Modelos implementados

- ARIMA
- SARIMAX
- Random Forest
- XGBoost
- LSTM
- Prophet

## Reproducibilidad

Los notebooks fueron estructurados para trabajar con rutas relativas al repositorio. Para reproducir el flujo del proyecto, se recomienda ejecutar los notebooks en el orden indicado anteriormente.

El dataset base utilizado en el estudio se encuentra en:

`data/raw/energy_weather_holidays_daily_2022_2025.csv`

Los archivos procesados, tablas y figuras generadas durante la ejecución se guardan en las carpetas `data/processed/` y `outputs/`.

## Requisitos

Las dependencias principales del proyecto se encuentran en el archivo `requirements.txt`.

## Autor

Jairo Lenin Otáñez Moreno  
Trabajo de Fin de Máster
