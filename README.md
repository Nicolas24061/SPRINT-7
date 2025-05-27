# SPRINT-7

# Cuadro de Mandos - Visualización de Datos con Streamlit

## Descripción

Esta aplicación web está diseñada para facilitar la exploración y visualización de un conjunto de datos a través de gráficos interactivos. Utilizando Streamlit junto con Plotly Express y Pandas, permite a los usuarios construir visualizaciones como histogramas y gráficos de dispersión con solo hacer clic en botones o seleccionar casillas de verificación.

## Funcionalidad

- Carga un conjunto de datos en formato CSV y muestra una vista previa de los datos.
- Permite construir un histograma de una columna numérica seleccionada mediante un botón o una casilla de verificación.
- Permite construir un gráfico de dispersión entre dos columnas numéricas mediante un botón o una casilla de verificación.
- Los gráficos son interactivos y se muestran directamente en la aplicación para facilitar el análisis visual.

## Cómo usar

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener Python instalado junto con las librerías: `streamlit`, `pandas` y `plotly`.
3. Coloca el archivo CSV con tus datos en el directorio raíz del proyecto.
4. Modifica el archivo `app.py` para ajustar la ruta del CSV y las columnas que deseas visualizar.
5. Ejecuta la aplicación con el comando:
   ```bash
   streamlit run app.py
