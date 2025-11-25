# Data-Sciense-I

# Proyecto de Visualización y Análisis de la Felicidad Mundial 🌍

## 📌 Descripción General

Este proyecto forma parte de la **Primera Entrega del Trabajo Final** del curso de Data Science.  
El objetivo es analizar el **World Happiness Report** utilizando técnicas de **visualización, análisis exploratorio y diagnóstico inicial del dataset**, aplicadas con Python.

Se busca responder la pregunta:
> *¿Qué factores socioeconómicos y sociales influyen en el nivel de felicidad de los países?*

---

## 🎯 Objetivos del Proyecto

✔ Realizar un **Abstract** descriptivo del problema (250–500 palabras)  
✔ Formular **preguntas e hipótesis** de interés basadas en los datos  
✔ Explorar el dataset con **resúmenes numéricos y detección de valores faltantes**  
✔ Generar visualizaciones **univariadas, bivariadas y multivariadas (3+ variables)**  
✔ Interpretar los gráficos y vincularlos directamente con las hipótesis  
✔ Dejar listo el notebook como avance para el análisis final del proyecto

---

## 📂 Dataset

| Característica | Detalle |
|----------------|---------|
| Fuente | Kaggle — World Happiness Report |
| Formato | CSV delimitado por `;` |
| Filas | Múltiples países, varios años |
| Variables principales | 10 |
| Objetivo | Evaluar cómo factores como PIB, salud, apoyo social, corrupción y libertad afectan la felicidad |

### 🔑 Variables clave utilizadas

| Variable | Descripción |
|----------|-------------|
| Happiness score | Nivel de felicidad (0 a 10) |
| GDP per capita | PIB per cápita (riqueza) |
| Healthy life expectancy | Expectativa de vida saludable |
| Social support | Apoyo social percibido |
| Freedom to make life choices | Libertad percibida |
| Perceptions of corruption | Confianza institucional |
| Regional indicator | Región geográfica |

---

## ❓ Preguntas e Hipótesis

| Pregunta | Hipótesis |
|----------|-----------|
| ¿El PIB influye en la felicidad? | A mayor PIB per cápita, mayor nivel de felicidad. |
| ¿La salud impacta en el bienestar? | Los países con mayor expectativa de vida son más felices. |
| ¿La corrupción reduce la felicidad? | Cuanto mayor la corrupción percibida, menor la felicidad. |
| ¿Factores combinados explican mejor la felicidad? | El bienestar aumenta cuando hay riqueza, salud y estabilidad regional. |

---

## 📊 Visualizaciones realizadas

| Tipo de gráfico | Contenido | Variables |
|------------------|----------|-----------|
| Univariado | Distribución felicidad | Happiness score |
| Bivariado | PIB vs Felicidad | GDP per capita / Happiness score |
| Bivariado | Salud vs Felicidad | Health / Happiness score |
| Bivariado | Corrupción vs Felicidad | Perceptions of corruption / Happiness score |
| Comparativo | Libertad y apoyo social vs felicidad | Freedom, Social support, Happiness |
| **Multivariado (3+)** | PIB, Salud y Felicidad (con tamaño) | GDP, Life expectancy, Happiness score, Región (opcional) |

---

## 🔍 Técnicas utilizadas

- 🧮 Pandas para manipulación de datos  
- 📊 Matplotlib & Seaborn para visualizaciones  
- 🧹 Análisis de valores faltantes con `isnull()`  
- 📈 Resumen estadístico con `describe()`  
- 🔎 Interpretación vinculada
