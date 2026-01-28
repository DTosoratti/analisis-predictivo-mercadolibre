# Análisis Predictivo – Clasificación de Productos en MercadoLibre

Proyecto realizado en el marco de la materia **Análisis Predictivo**.  
El objetivo es desarrollar un modelo de **clasificación binaria** para predecir si una publicación de MercadoLibre corresponde a un **producto nuevo o usado**, a partir de información textual y estructurada.

El trabajo aborda el **proceso completo de ciencia de datos**, desde la exploración inicial hasta la evaluación de distintos modelos predictivos.

---

## 📊 Dataset

- **Fuente:** MercadoLibre  
- **Tipo de datos:** Publicaciones de productos
- **Variables:**  
  - Título y atributos del producto  
  - Información de envío  
  - Categoría  
  - Datos del vendedor  
  - Etiqueta objetivo: *nuevo / usado*

Los archivos incluidos en este repositorio corresponden a **datasets preprocesados**, listos para ser utilizados en los modelos.

---

## 🧪 Metodología

El proyecto se desarrolló siguiendo un enfoque iterativo, compuesto por las siguientes etapas:

1. **Análisis Exploratorio de Datos (EDA)**
2. **Limpieza y preprocesamiento**
3. **Feature engineering**
4. **Entrenamiento de modelos**
5. **Evaluación y comparación de desempeño**

---

## 📁 Contenido del repositorio

### 📌 Presentación
- `analisis_predictivo_ml_examen3.pptx`  
  Presentación del proyecto con la explicación completa del enfoque, decisiones metodológicas y resultados obtenidos.

### 📓 Notebooks
- Implementación del modelo con mejor desempeño

El modelo final de referencia es **CatBoost**, seleccionado por su rendimiento y capacidad de generalización.

## 🤖 Modelos evaluados

- Logistic Regression  
- Linear SVC  
- Modelos basados en árboles  
- **CatBoost** (mejor desempeño)

---

## 📈 Evaluación

Los modelos fueron evaluados mediante métricas de clasificación, priorizando:
- Accuracy
- Comparación entre modelos
- Robustez frente a distintos conjuntos de features

---

## 📂 Archivos adicionales (Google Drive)

Algunos archivos del proyecto (notebooks con outputs completos y datasets de mayor tamaño) superan el límite de tamaño permitido por GitHub.

📎 Carpeta completa del proyecto:  
🔗 **https://drive.google.com/drive/folders/1_i2bQGYM2lesOHxKK7GKyC4Wxb-dMxKi?usp=sharing**

---

## 🧠 Conclusiones

- El **feature engineering** tuvo un impacto determinante en el desempeño de los modelos.
- Los modelos basados en árboles superaron a los enfoques lineales.
- CatBoost ofreció el mejor equilibrio entre performance y estabilidad.
- El proyecto refleja un proceso experimental e iterativo propio de un flujo real de análisis predictivo.

---

## 👤 Autor

**Dante Tosoratti**
