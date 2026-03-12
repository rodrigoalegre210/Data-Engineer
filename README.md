<h1 align="center"> 🛠️ Data Engineering Pipeline: ETL & SQL Ingestion </h1>

> **Proyecto Individual Nº1** - Etapa de Laboratorios (Henry Bootcamp)
> 
> **Rol:** Data Engineer

---

## 📄 Descripción del Proyecto

Este proyecto consiste en el diseño y ejecución de un proceso de **ETL (Extract, Transform, Load)** para un sistema de gestión de precios. El desafío principal radicó en la normalización de archivos de diversos formatos, la automatización de la carga hacia **MySQL** mediante scripts de Python y la unificación de datasets incrementales para realizar consultas analíticas complejas.

### Objetivos Clave:
* **Normalización de Formatos:** Conversión y estandarización de archivos heterogéneos a CSV.
* **Automatización de Ingesta:** Desarrollo de funciones en Python para migrar datos a SQL sin intervención manual.
* **Integración de Datos:** Unificación de múltiples archivos de precios semanales para análisis histórico.

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Herramientas |
|-----------|--------------|
| **Lenguaje** | Python (Pandas, NumPy) |
| **Orquestación** | SQLAlchemy (`create_engine`) |
| **Base de Datos** | MySQL Workbench |
| **Entorno** | Jupyter Notebook |

---

## ⚙️ Arquitectura del Proyecto

### 1. Proceso de ETL
- **Extracción:** Lectura de archivos fuente en diversos formatos.
- **Transformación:** Limpieza de imperfecciones, manejo de nulos y estandarización de columnas.
- **Carga (Load):** Implementación de una conexión robusta entre Python y MySQL para la creación dinámica de tablas.

### 2. Automatización con Python
Se desarrolló una función personalizada que utiliza **SQLAlchemy** para:
1. Validar la existencia de la tabla en el motor SQL.
2. Ingestar el DataFrame procesado de manera eficiente.

### 3. Resolución de Caso de Negocio
Para validar el pipeline, se realizó una consulta de agregación sobre el dataset unificado:
- **Query:** Cálculo del precio promedio de la sucursal `9-1-688`.
- **Resultado obtenido:** `203.8`

---

## 📊 Flujo de Trabajo

<p align="center">
  <img src="https://user-images.githubusercontent.com/105827215/198372532-0f5212a3-a2ed-49bb-9db3-522b8e476740.png" alt="Diagrama de Flujo" width="700">
</p>

---

## 📺 Demo y Explicación

Podes ver el funcionamiento detallado del script y la arquitectura de la base de datos en el siguiente video:

▶️ **[Ver video explicativo del proyecto](https://www.youtube.com/watch?v=-jOQH-hUPYY&t=8s)**

---

<h3 align="center">🚀 Desarrollado por Rodrigo - Data Science & AI Engineer 🚀</h3>
