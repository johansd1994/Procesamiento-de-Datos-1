# Procesamiento de Datos con Pandas

Este repositorio contiene un **Jupyter Notebook** enfocado en el **procesamiento, limpieza y análisis exploratorio de datos (EDA)** del dataset clásico de **enfermedades cardíacas (Heart Disease – Cleveland Dataset)**, utilizando **Python y Pandas**.

El notebook fue desarrollado con fines **académicos y prácticos**, mostrando paso a paso un flujo básico de preparación de datos para análisis y modelado posterior.

---

## 📌 Contenido del Notebook

El archivo principal del repositorio es:

* `Procesamiento de Datos 1.ipynb`

En él se desarrollan las siguientes etapas:

### 1️⃣ Carga de librerías

Se utilizan principalmente:

* `pandas` para manipulación y análisis de datos

---

### 2️⃣ Definición del esquema de datos

Se asignan explícitamente los nombres de las columnas del dataset, garantizando que cada variable corresponda correctamente a su significado original:

* Edad (`age`)
* Sexo (`sex`)
* Tipo de dolor en el pecho (`cp`)
* Presión arterial en reposo (`trestbps`)
* Colesterol (`chol`)
* Azúcar en sangre en ayunas (`fbs`)
* Resultados del electrocardiograma (`restecg`)
* Frecuencia cardíaca máxima (`thalach`)
* Angina inducida por ejercicio (`exang`)
* Depresión del ST (`oldpeak`)
* Pendiente del ST (`slope`)
* Número de vasos coloreados (`ca`)
* Talasemia (`thal`)
* Variable objetivo – diagnóstico (`num`)

---

### 3️⃣ Carga del dataset

El dataset utilizado es:

* `processed.cleveland.data`

Este archivo corresponde a una versión preprocesada del **Heart Disease Dataset** ampliamente usado en estudios de ciencia de datos y machine learning.

---

### 4️⃣ Exploración inicial de los datos

Se realiza una revisión básica para comprender la estructura del dataset:

* Visualización de las primeras filas
* Dimensiones del dataset (filas y columnas)
* Tipos de datos de cada variable

---

### 5️⃣ Limpieza de datos

Durante esta etapa se trabajan aspectos clave como:

* Identificación de valores faltantes
* Reemplazo de valores inválidos (por ejemplo `?`)
* Conversión de tipos de datos
* Eliminación o tratamiento de registros incompletos

Esta fase es fundamental para asegurar la **calidad y consistencia de los datos** antes de cualquier análisis posterior.

---

### 6️⃣ Análisis exploratorio (EDA)

El notebook incluye análisis descriptivo que permite:

* Entender la distribución de las variables
* Identificar patrones relevantes
* Analizar la variable objetivo relacionada con enfermedades cardíacas

Este análisis sirve como base para futuras etapas de **modelado predictivo**.

---

## 🛠️ Requisitos

Para ejecutar el notebook se requiere:

* Python 3.8 o superior
* Jupyter Notebook o Jupyter Lab
* Librerías:

  ```bash
  pip install pandas
  ```

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:

   ```bash
   git clone <url-del-repositorio>
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd <nombre-del-repositorio>
   ```

3. Abre el notebook:

   ```bash
   jupyter notebook
   ```

4. Ejecuta las celdas en orden.

---

## 🎯 Objetivo del proyecto

El objetivo principal es **demostrar un flujo completo de procesamiento de datos**, desde la carga hasta la limpieza y exploración, aplicando buenas prácticas en Pandas.

Este notebook puede servir como:

* Material de estudio
* Base para modelos de Machine Learning
* Ejemplo de preprocesamiento de datos reales

---

## 📚 Dataset

El dataset utilizado proviene del **UCI Machine Learning Repository – Heart Disease Dataset (Cleveland)**.

---

## ✍️ Autor

**Johan Suarez**

---

## 📄 Licencia

Este proyecto se comparte con fines educativos. Puedes reutilizarlo y adaptarlo libremente citando la fuente.

---

⭐ Si este repositorio te resulta útil, ¡no olvides darle una estrella en GitHub!
