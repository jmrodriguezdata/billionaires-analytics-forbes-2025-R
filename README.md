# billionaires-analytics-forbes-2025-R #


**Autor:** Juan Miguel Rodríguez Trujillo  
**Fecha:** Mayo 2025  

---

## 📌 Descripción del proyecto

Este repositorio contiene un **proyecto de analítica descriptiva en R** que analiza la **distribución global de la riqueza extrema** utilizando la lista de multimillonarios publicada por **Forbes en 2025**.

A partir de un enfoque cuantitativo y visual, el proyecto explora cómo se concentra la riqueza a nivel **geográfico**, **industrial** y **regional**, combinando estadísticas descriptivas con visualizaciones tradicionales y **mapas geoespaciales**.

---

## 🎯 Objetivo general

Analizar y visualizar la distribución mundial de la riqueza extrema en 2025 mediante técnicas de análisis descriptivo y visualización de datos en R.

---

## 🎯 Objetivos específicos

- Explorar las principales características del dataset de multimillonarios de Forbes 2025.
- Identificar los países con mayor número de multimillonarios.
- Analizar la distribución de la riqueza por **industria económica**.
- Comparar la concentración de multimillonarios entre **Estados Unidos, China y Europa**.
- Evaluar la posición de **Colombia** frente a otros países latinoamericanos.
- Visualizar la distribución geográfica de los multimillonarios mediante **mapas temáticos**.

---

## 📊 Dataset

- **Fuente:** Forbes – World’s Billionaires List 2025  
- **Observaciones:** 3.077 multimillonarios  
- **Variables principales:**
  - `Rank`
  - `Name`
  - `NetWorth` (USD billones)
  - `Age`
  - `Country`
  - `Source`
  - `Industry`

> ⚠️ El archivo original de Forbes no se incluye en este repositorio por restricciones de derechos y tamaño.

---

## 🛠️ Herramientas y librerías utilizadas

El proyecto fue desarrollado en **R** utilizando principalmente:

- `dplyr`
- `tidyverse`
- `ggplot2`
- `stringr`
- `kableExtra`
- `ggrepel`
- `treemapify`
- `rnaturalearth`
- `sf`
- `readxl`

---

## 🌐 Análisis realizados

- Estadísticas descriptivas de patrimonio y edad.
- Ranking de países con mayor número de multimillonarios.
- Análisis por industria:
  - Número de multimillonarios.
  - Patrimonio neto agregado.
- Comparaciones regionales y geopolíticas:
  - Estados Unidos vs China vs Europa.
  - Colombia vs países latinoamericanos.
- Visualizaciones geoespaciales de la concentración de riqueza:
  - Mapa mundial.
  - Mapas regionales (América, Europa y Asia).

---

## 📁 Estructura del repositorio

```text
├── data/
│   └── (dataset no incluido)
├── scripts/
│   └── Analytics_Project.Rmd
├── outputs/
│   └── Analytics-Project.html
├── README.md
