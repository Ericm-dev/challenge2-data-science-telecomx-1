# Telecom X — Análisis de Churn

## Índice

* [Descripción del Proyecto](#descripción-del-proyecto)
* [Objetivo](#objetivo)
* [Dataset](#dataset)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Proceso del Proyecto](#proceso-del-proyecto)
* [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
* [Resultados](#resultados)
* [Posibles Mejoras](#posibles-mejoras)
* [Autor](#autor)

---

## Descripción del Proyecto

Este proyecto presenta un análisis exploratorio de datos (EDA) sobre la evasión de clientes (Churn) en la empresa Telecom X.

El objetivo es identificar patrones y factores asociados a la cancelación del servicio utilizando Python y sus principales bibliotecas de análisis de datos.

El proyecto fue desarrollado en Google Colab.

---

## Objetivo

Comprender los factores que influyen en la cancelación de clientes y generar información que permita desarrollar estrategias de retención y futuros modelos predictivos de churn.

---

## Dataset

Los datos fueron obtenidos desde una API en formato JSON.

El dataset contiene información sobre:
* Clientes
* Servicios contratados
* Facturación
* Tipo de contrato
* Método de pago
* Antigüedad del cliente
* Variable objetivo: Churn

---

## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Plotly
* Requests
* Google Colab

---

## Proceso del Proyecto

### Extracción de Datos

* Obtención de datos desde una API
* Conversión de JSON a DataFrame

### Limpieza y Transformación

* Revisión de tipos de datos
* Manejo de valores nulos
* Estandarización de variables categóricas
* Conversión de variables numéricas
* Renombrado de columnas
* Creación de variables derivadas

### Análisis Exploratorio de Datos (EDA)

Se realizaron visualizaciones para analizar:

* Distribución de churn
* Churn por tipo de contrato
* Churn por antigüedad del cliente
* Churn por método de pago
* Churn por servicio de internet

---

## Cómo Ejecutar el Proyecto

1. Abrir el notebook en Google Colab
2. Ejecutar las celdas en orden

[https://colab.research.google.com/](https://colab.research.google.com/)

---

## Resultados

El análisis permitió identificar variables asociadas a la evasión de clientes, especialmente:

* Tipo de contrato
* Antigüedad del cliente
* Método de pago
* Características del servicio

Estos resultados pueden servir como base para modelos predictivos de churn.
---

## Posibles Mejoras

* Construcción de un modelo de Machine Learning
* Dashboard interactivo
* Pipeline ETL automatizado
* Validación estadística de variables

---

## Autor
Ericm-Dev
Proyecto desarrollado como práctica de análisis de datos.
