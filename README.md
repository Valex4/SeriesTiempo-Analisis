# Análisis de Series Temporales: Predicción de Ingresos en Carreteras y Puentes de México

## Descripción
Este proyecto implementa tres modelos de series temporales (Prophet, Holt-Winters y ARIMA) para analizar y predecir los ingresos en diferentes tramos carreteros y puentes de México. El análisis cubre datos desde 2021 hasta 2024, con predicciones para los siguientes seis meses.

## Modelos Implementados
- **Prophet**: Desarrollado por Meta, especializado en series temporales con estacionalidad
- **Holt-Winters**: Método de suavizado exponencial con componentes estacionales
- **ARIMA**: Modelo autorregresivo integrado de media móvil

## Requisitos
```python
pandas==2.0.0
numpy==1.24.3
prophet==1.1.4
statsmodels==0.14.0
scikit-learn==1.3.0
matplotlib==3.7.1 
```
## Instalacion y Configuración

1. Clonar el repositorio:

```
git clone https://github.com/Valex4/SeriesTiempo-Analisis
cd SeriesTiempo-Analisis
```

2. Crear y activar entorno virtual:

```
python3 -m venv venv
source venv/bin/activate  # En Unix/macOS
# o
venv\Scripts\activate  # En Windows
```

3. Instalar dependencias:

``pip install -r requirements.txt``

## Estructura del Código

- **prepare_data_prophet( )**: Prepara datos para el modelo Prophet
- **evaluate_model( )**: Calcula métricas de rendimiento
- **forecast_models( )**: Implementa los tres modelos de predicción
- **plot_forecasts( )**: Genera visualizaciones comparativas
- **analizar_tramo( )**: Función principal para análisis individual

## Ejecución

Para la ejecución del codigo primeramente debemos de crear nuestro entorno virutal para posteriomente poder instalar las librerias que utilizaremos.

El archivo ``FinalSeriesTiempo.ipynb`` es el Notebook el cual contiene todo el codigo. Unicamente ejecuta las celdas secuencialmente.

En la carpeta `ImagenesObtenidas` se encuentran los resultados de las imagenes que previamente se han obtenido a partir de la ejecución de codigo.