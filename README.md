# Análisis de ventas con Python

## 1. Descripción del proyecto

Este proyecto consiste en analizar un conjunto de datos de ventas de una tienda minorista utilizando Python. El objetivo principal es explorar la información, identificar patrones de comportamiento, calcular medidas estadísticas y representar los resultados mediante gráficos.

## 2. Objetivos del proyecto

- Explorar y comprender el conjunto de datos.
- Limpiar y preparar los datos para su análisis.
- Calcular medidas estadísticas descriptivas.
- Analizar las ventas por categoría de producto y por mes.
- Identificar posibles valores atípicos.
- Crear gráficos para visualizar los resultados.

## 3. Tecnologías y herramientas utilizadas

- **Python 3.11:** lenguaje de programación utilizado.
- **Pandas:** manipulación y análisis de datos.
- **NumPy:** cálculos numéricos y estadísticos.
- **Matplotlib:** creación de gráficos y visualizaciones.
- **Jupyter Notebook:** entorno interactivo para desarrollar el análisis.
- **Visual Studio Code:** editor de código utilizado.

## 4. Descripción del conjunto de datos

Se utilizó un conjunto de datos de ventas minoristas que contiene 1.000 transacciones.

La información incluye:

- Fecha de cada transacción.
- Género y edad del cliente.
- Categoría del producto.
- Cantidad de unidades compradas.
- Precio por unidad.
- Importe total de cada venta.

## 5. Configuración del entorno de desarrollo

Para mantener las dependencias del proyecto organizadas e independientes de otras instalaciones de Python, se creó un entorno virtual utilizando el módulo `venv`.

### Creación del entorno virtual

```powershell
# Creamos un entorno virtual llamado .venv
python -m venv .venv
```

### Activación del entorno virtual

En Windows, utilizando PowerShell:

```powershell
# Activamos el entorno virtual
.\.venv\Scripts\Activate.ps1
```

### Instalación de librerías

Con el entorno virtual activado, se instalaron las herramientas necesarias:

```powershell
# Instalamos Pandas
pip install pandas

# Instalamos NumPy
pip install numpy

# Instalamos Matplotlib
pip install matplotlib

# Instalamos Jupyter Notebook
pip install notebook
```

### Archivo de dependencias

Se creó un archivo `requirements.txt` para documentar las librerías principales y sus versiones.

Para instalar las dependencias en otro entorno:

```powershell
# Instalamos las dependencias del proyecto
pip install -r requirements.txt
```

### Desactivación del entorno virtual

Cuando se termina de trabajar en el proyecto, el entorno puede desactivarse mediante:

```powershell
# Desactivamos el entorno virtual
deactivate
```

## 6. Estructura del proyecto

```text
analizador_ventas/
│
├── .venv/
│
├── data/
│   └── Sales Dataset.csv
│
├── analisis_ventas.ipynb
├── README.md
└── requirements.txt
```

## 7. Análisis realizados

Durante el desarrollo del proyecto se realizaron las siguientes tareas:

- Exploración y limpieza de datos.
- Cálculo de medidas estadísticas: promedio, mediana, moda, varianza y desviación estándar.
- Análisis de cuartiles y rango intercuartílico (IQR).
- Detección de posibles valores atípicos.
- Análisis de ventas mensuales.
- Análisis de ventas por categoría de producto.
- Creación de gráficos de barras, histogramas y diagramas de caja (Boxplot).
- Realización de cálculos numéricos utilizando NumPy.

## 8. Principales resultados

- Las ventas totales alcanzaron las 456.000 unidades monetarias.
- La categoría Electrónica registró la mayor facturación, con 156.905.
- Mayo fue el mes con mayores ventas, con 53.150.
- No se detectaron valores atípicos mediante el criterio de 1,5 × IQR.

## 9. Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir una terminal dentro de la carpeta del proyecto.
3. Crear el entorno virtual siguiendo las instrucciones de la sección 5.
4. Activar el entorno virtual.
5. Instalar las dependencias con `pip install -r requirements.txt`.
6. Abrir el notebook con Visual Studio Code o iniciar Jupyter Notebook.
7. Ejecutar las celdas de `analisis_ventas.ipynb`.

## 10. Autor
##MIKHAIL ACEVEDO

Proyecto académico individual desarrollado como parte de un trabajo práctico de Python.