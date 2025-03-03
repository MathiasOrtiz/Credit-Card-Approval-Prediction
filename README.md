# 🏦 Credit Card Approval Prediction Project

This project applies **Machine Learning and Deep Learning** to predict whether a credit card application will be approved or rejected. Various models and preprocessing techniques were tested to determine the most efficient and accurate approach.

## 📊 Project Description

We worked with a dataset containing financial and personal information of credit card applicants. Several classification models were implemented, including:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Random Forest**
- **XGBoost**
- **Neural Network (MLP)**

After evaluating the results, **Random Forest** proved to be the best-performing model, showing the highest accuracy and generalization capability.

## 🔧 Data Preprocessing

Before training the models, the following preprocessing steps were performed:

- **Outlier removal** (capping)
- **Transformation of skewed variables** (log transformation)
- **Normalization of numerical variables** (StandardScaler)
- **Encoding categorical variables** (One-Hot Encoding)

## 🏆 Results

After testing and comparing different models, **Random Forest** was found to be the most effective, achieving **86.23% accuracy on the test set**. The neural network performed similarly but showed signs of overfitting.

### 📌 Model Performance Comparison:

| Model               | Accuracy |
|---------------------|----------|
| **Random Forest**  | **86.23%** |
| K-Nearest Neighbors (KNN) | 83.33% |
| XGBoost            | 82.61% |
| Logistic Regression | 83.33% |
| Decision Tree      | 74.64% |
| Neural Network (MLP) | 83.33% |

## 📜 License

This project is licensed under the **MIT License**, allowing for use, modification, and distribution. See the **LICENSE** file for more details.

---

# 🏦 Proyecto de Aprobación de Tarjetas de Crédito

Este proyecto utiliza **Machine Learning y Deep Learning** para predecir si una solicitud de tarjeta de crédito será aprobada o rechazada. Se han aplicado diferentes modelos y técnicas de preprocesamiento para evaluar cuál es el más eficiente y preciso.

## 📊 Descripción del Proyecto

Se ha trabajado con un conjunto de datos que contiene información financiera y personal de los solicitantes de tarjetas de crédito. Se implementaron distintos modelos de clasificación, incluyendo:

- **Regresión Logística**
- **K-Nearest Neighbors (KNN)**
- **Árbol de Decisión**
- **Random Forest**
- **XGBoost**
- **Red Neuronal (MLP)**

Después de evaluar los resultados, **Random Forest** fue el modelo con mejor desempeño, mostrando una mayor precisión y mejor capacidad de generalización.

## 🔧 Preprocesamiento de Datos

Antes de entrenar los modelos, se realizaron los siguientes pasos de preprocesamiento:

- **Eliminación de valores atípicos** (capping)
- **Transformación de variables sesgadas** (log transformation)
- **Normalización de variables numéricas** (StandardScaler)
- **Codificación de variables categóricas** (One-Hot Encoding)

## 🏆 Resultados

Tras probar y comparar diferentes modelos, se concluyó que **Random Forest** era el más efectivo, obteniendo una **precisión del 86.23% en el conjunto de prueba**. La red neuronal mostró un rendimiento cercano, pero con indicios de sobreajuste.

### 📌 Comparación de Desempeño de Modelos:

| Modelo                | Precisión |
|----------------------|----------|
| **Random Forest**   | **86.23%** |
| K-Nearest Neighbors (KNN) | 83.33% |
| XGBoost             | 82.61% |
| Regresión Logística | 83.33% |
| Árbol de Decisión   | 74.64% |
| Red Neuronal (MLP)  | 83.33% |

## 📜 Licencia

Este proyecto está bajo la licencia **MIT**, lo que permite su uso, modificación y distribución. Consulta el archivo **LICENSE** para más detalles.
