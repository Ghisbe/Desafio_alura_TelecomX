# Desafío Alura: Telecom X - Análisis de cancelaciones de clientes

Este proyecto forma parte de los desafíos de **Alura Latam** para el programa **Oracle Next Education (ONE)**. Se centra en el análisis de cancelaciones en una empresa de telecomunicaciones utilizando Python y técnicas de manipulación de datos.

## Descripción del Proyecto
El objetivo principal es preparar, limpiar y explorar un dataset real para comprender el comportamiento de los clientes y sentar las bases para futuros modelos predictivos. Todo el proceso, desde la carga de datos hasta la visualización e interpretación, está documentado detalladamente en el notebook.

### Objetivos
* **Analizar** el fenómeno de cancelaciones de manera integral.
* **Transformar** datos crudos en información útil para el negocio.
* **Identificar** patrones y relaciones entre servicios, costos y permanencia.

---

## Información del Dataset
* **Formato:** JSON
* **Registros finales:** 7,043 clientes
* **Variable Objetivo:** `Churn` (Evasión)

> [!IMPORTANT]
> El archivo de datos no se genera automáticamente. Es necesario descargar **`TelecomX_Data.json`** y cargarlo en el entorno antes de ejecutar el código.

---

## Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn.
* **Entorno:** Google Colab / Jupyter Notebook.

---

## Estructura del Proyecto
```bash
Desafrio_alura_TelecomX
│
├──  Desafio_telecom.ipynb    # Limpieza, EDA y visualizaciones
├──  TelecomX_Data.json       # Dataset (Requiere carga manual)
└──  README.md                # Descripción del proyecto

```
---

## Instrucciones para ejecutar el proyecto en Google Colab
Opción 1: Ejecutar desde GitHub en Colab (recomendado)
- Abrir el repositorio en GitHub.
- Hacer clic en el archivo Desafio_telecomX.ipynb.
- Seleccionar “Open in Colab” o pegar la URL del notebook en:
```bash
https://colab.research.google.com/drive/14i7XbMBxqEiosOIUMEE5hbz5cy5x8ftq?usp=sharing
```
- Descargar el archivo TelecomX_Data.json.
- Subir el archivo JSON al entorno de Colab (o a Google Drive).
- Verificar o ajustar la ruta del archivo en el notebook si es necesario.
- Ejecutar las celdas en orden desde el inicio.

Opción 2: Ejecutar el proyecto localmente en Colab
- Descargar o clonar el repositorio:
```bash
git clone https://github.com/Ghisbe/Desafio_alura_TelecomX.git
```
- Subir el archivo Desafio_telecom.ipynb a Google Colab.
- Descargar el archivo TelecomX_Data.json.
- Subir el archivo JSON al entorno de Colab o conectarlo desde Google Drive.
- Ejecutar todas las celdas del notebook.

## Notas adicionales:
El notebook contiene:
- Proceso completo de limpieza y transformación de datos.
- Análisis exploratorio con visualizaciones.
- Interpretación de resultados.
- No se requiere configuración adicional ni librerías externas fuera del entorno estándar de Google Colab.

👤Autora
Gisela Figueroa
