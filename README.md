# Data-Sciense-I

# Proyecto Final – Análisis y Modelado de la Felicidad Mundial 🌍

## 📌 Descripción General

Este repositorio contiene los trabajos realizados durante la cursada de **Data Science I**, culminando en un **proyecto final** basado en el análisis del *World Happiness Report*.

El proyecto comenzó como un ejercicio de **visualización y análisis exploratorio**, y evolucionó hacia un enfoque de **modelado predictivo**, aplicando técnicas de ciencia de datos para comprender qué factores influyen en el nivel de felicidad de los países.

Pregunta central del análisis:
> *¿Qué variables socioeconómicas y sociales influyen en el nivel de felicidad de los países y en qué medida pueden predecirse a partir de los datos disponibles?*

---

## 🎯 Objetivo del Proyecto

Analizar los factores asociados al nivel de felicidad de los países y desarrollar un modelo de aprendizaje automático capaz de **predecir el puntaje de felicidad** a partir de variables económicas, sociales y de bienestar.

---

## 🏢 Contexto

El análisis se plantea desde la perspectiva de una organización interesada en evaluar el bienestar de distintos países para apoyar la toma de decisiones vinculadas a políticas públicas, desarrollo social y calidad de vida.

---

## 📂 Dataset

| Característica | Detalle |
|----------------|---------|
| Fuente | Kaggle — World Happiness Report |
| Formato | CSV |
| Observaciones | Países a lo largo de distintos años |
| Variables principales | Indicadores económicos, sociales y de salud |
| Variable objetivo | Happiness score |

### 🔑 Variables clave utilizadas

| Variable | Descripción |
|----------|-------------|
| Happiness score | Nivel de felicidad (0 a 10) |
| GDP per capita | PIB per cápita |
| Healthy life expectancy | Expectativa de vida saludable |
| Social support | Apoyo social percibido |
| Freedom to make life choices | Libertad percibida |
| Perceptions of corruption | Corrupción percibida |

---

## ❓ Hipótesis de Trabajo

- Existe una relación positiva entre el PIB per cápita y el nivel de felicidad.
- Los países con mayor expectativa de vida saludable presentan mayores niveles de bienestar.
- Una mayor percepción de corrupción se asocia con menores niveles de felicidad.
- La felicidad puede explicarse mejor a partir de la combinación de múltiples factores socioeconómicos.

Estas hipótesis fueron evaluadas mediante análisis exploratorio y modelado predictivo.

---

## 📊 Análisis Exploratorio de Datos (EDA)

El EDA incluyó:
- Exploración inicial del dataset y estructura de los datos
- Análisis de variables numéricas y estadísticas descriptivas
- Detección y análisis de valores faltantes
- Visualizaciones univariadas y bivariadas
- Análisis de correlaciones entre variables
- Evaluación de relaciones entre las variables explicativas y el puntaje de felicidad

No se eliminaron valores atípicos, ya que representan países reales y no errores de medición.

---

## 🔍 Selección de Variables

La selección de variables se realizó combinando:
- análisis de correlación,
- visualizaciones exploratorias,
- y criterio experto,

priorizando aquellas variables con mayor relación con la variable objetivo.

---

## 🤖 Modelado

Se entrenaron y compararon dos modelos de regresión:
- **Ridge Regression**, como modelo lineal base
- **Random Forest Regressor**, para capturar relaciones no lineales entre las variables

---

## 📈 Métricas de Evaluación

Los modelos fueron evaluados utilizando:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Coeficiente de determinación)

El modelo Random Forest presentó un mejor desempeño general.

---

## 🧾 Conclusiones

Los resultados muestran que la felicidad es un fenómeno multifactorial influenciado por variables económicas, sociales y de salud.  
El análisis exploratorio y el modelado permitieron identificar patrones relevantes y desarrollar un modelo con buen desempeño predictivo, destacándose el enfoque no lineal frente al modelo lineal base.

---

## 🛠️ Herramientas Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 👤 Autor

**Jeremías Davison**  
Proyecto desarrollado como parte de la cursada de *Data Science I*.
