# Analisis-V1

El archivo Backtesting_V1ipynb.ipynb en tu repositorio de GitHub es un notebook de Jupyter que contiene código Python para realizar backtesting de una estrategia de trading en el mercado de acciones. Aquí está un resumen de lo que hace el código:

Instalación de librerías y montaje de Google Drive: El código comienza instalando la librería ta para análisis técnico y montando Google Drive para acceder a los datos.

Importación de librerías y descarga de datos: Importa varias librerías como numpy, pandas, matplotlib, yfinance y varias funciones de la librería ta. Luego, descarga los datos de precios de una acción específica (en este caso, Apple) usando yfinance.

Definición de estrategia de trading: Define una estrategia de trading basada en el indicador ADX (Average Directional Index). La estrategia genera señales de compra y venta basadas en el cruce de las líneas +DI y -DI del indicador ADX.

Ejecución de la estrategia y registro de operaciones: Ejecuta la estrategia en los datos descargados y registra cada operación en un DataFrame de pandas. Cada operación incluye detalles como la fecha de compra, el precio de compra, la cantidad comprada, la fecha de venta, el tipo de venta, el precio de venta, el capital final, los días de operación, el resultado y el resultado porcentual.

Cálculo de indicadores de rendimiento: Finalmente, calcula varios indicadores de rendimiento como el resultado final, el número de operaciones positivas, la mayor ganancia, la mayor pérdida, el CAGR (Compound Annual Growth Rate), la volatilidad, el ratio de Sharpe y el ratio de Sortino.
