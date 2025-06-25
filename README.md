# 📱 Users Classification – Ultra vs Smart  
## 📊 Clasificación de usuarios por tipo de plan móvil

Este proyecto utiliza técnicas de aprendizaje automático para clasificar a los usuarios de una compañía de telefonía móvil según el plan que mejor se adapta a su comportamiento: **Ultra** o **Smart**.  
This project applies machine learning techniques to classify mobile users into the most suitable plan based on their behavior: **Ultra** or **Smart**.

---

## 🎯 Objetivos / Objectives

- Analizar datos históricos de uso de clientes.  
- Entrenar y comparar modelos de clasificación.  
- Evaluar métricas de rendimiento como precisión, recall y AUC-ROC.  
- Ajustar el umbral de decisión para mejorar la sensibilidad del modelo.  

- Analyze customer usage data.  
- Train and compare classification models.  
- Evaluate performance metrics such as accuracy, recall, and AUC-ROC.  
- Tune the decision threshold to improve model sensitivity.

---

## 🧰 Herramientas / Tools Used

- Python 3  
- Pandas, NumPy  
- Scikit-learn (Logistic Regression, Random Forest)  
- Matplotlib, Seaborn  
- Jupyter Notebook

---

## 🧠 Enfoque / Approach

1. **Análisis exploratorio (EDA):**  
   - Revisión de distribuciones, correlaciones y valores faltantes.  
   - Visualización de patrones de uso.

2. **Modelado predictivo:**  
   - Entrenamiento de modelos supervisados (Regresión Logística y Random Forest).  
   - Validación del modelo con conjunto de prueba.

3. **Ajuste del umbral de decisión:**  
   - Uso de `predict_proba` para modificar el threshold y encontrar el punto óptimo entre precisión y recall.

---

## 📈 Resultados / Results

- **Modelo seleccionado:** Random Forest (`max_depth=11`, `n_estimators=300`)  
- **Métricas principales:** *(rellena con tus valores)*  
  - Accuracy: `XX%`  
  - ROC AUC: `XX`  
  - Recall: `XX%`  
- **Importancia de características:** duración de llamadas, mensajes enviados, uso de datos móviles.

---

## 📁 Estructura del proyecto / Project Structure

users-classification-ultra-smart/
├── ultra_smart_classifier.ipynb # Notebook principal
├── data/ # Datos (si están incluidos)
└── README.md # Este archivo


---

## 🚀 Lecciones aprendidas / Lessons Learned

- Cómo construir un pipeline de clasificación desde cero.  
- Comparar modelos usando métricas clave.  
- Cómo ajustar el umbral de decisión para mejorar el desempeño según la necesidad del negocio.  
- Aplicación práctica de Random Forest y visualización de resultados.

---

📫 ¿Tienes preguntas o sugerencias?  
Conectemos por [LinkedIn](https://www.linkedin.com/in/jovan-espinosa-llaguno-b04b0663/)
