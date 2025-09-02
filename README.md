# Telco Customer Churn Prediction 🔎

Este proyecto tiene como objetivo predecir qué clientes de una empresa de telecomunicaciones tienen mayor probabilidad de cancelar sus servicios (churn), utilizando técnicas de Machine Learning aplicadas a un conjunto de datos realista.

## 📊 Descripción del Dataset

El dataset **Telco Customer Churn** incluye información sobre:
- Clientes que han cancelado el servicio (`Churn`)
- Servicios contratados (Internet, Seguridad en línea, Backup, etc.)
- Información de cuenta (tiempo como cliente, contrato, método de pago, facturación)
- Datos demográficos (género, pareja, dependientes)

📁 Archivo: `Telco-Customer-Churn.csv`  
🔗 [Descargar dataset desde Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🎯 Objetivos del Proyecto

- Explorar los factores que influyen en la pérdida de clientes.
- Identificar patrones de comportamiento asociados al churn.
- Entrenar y comparar distintos modelos clasificadores.
- Interpretar los modelos con técnicas de explicabilidad (e.g. SHAP).
- Generar recomendaciones para reducir el churn.

## ⚙️ Tecnologías y Librerías

- Python 3
- pandas, numpy, seaborn, matplotlib
- scikit-learn
- XGBoost, LightGBM, AdaBoost, Gradient Boosting
- imbalanced-learn (SMOTE y SMOTEENN)
- SHAP (opcional para interpretación)

## 📌 Metodología

1. **Exploración y limpieza de datos**
2. **Análisis de valores faltantes**
3. **Codificación de variables categóricas**
4. **Normalización de variables numéricas**
5. **Balanceo de clases con SMOTE y SMOTEENN**
6. **Entrenamiento de múltiples modelos:**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - KNN
   - SVM
   - XGBoost
   - LightGBM
   - AdaBoost
   - Gradient Boosting
7. **Evaluación de modelos con F1-score, ROC-AUC, etc.**
8. **Interpretación con Feature Importance / SHAP (opcional)**

## 📈 Resultados

- Los modelos más robustos frente al desbalance fueron los ensembles: **Random Forest**, **XGBoost** y **LightGBM**.
- El uso de técnicas de oversampling como **SMOTE** y **SMOTEENN** permitió mejorar significativamente el desempeño.
- El F1-score fue la métrica principal, dada la importancia de capturar clientes que realmente abandonan.

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/telco-churn-prediction.git
   cd telco-churn-prediction
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## 📌 Requisitos

- Python 3.8 o superior  
- Jupyter Notebook  
- Bibliotecas especificadas en \`requirements.txt\`

## 📄 Licencia

Este proyecto fue desarrollado con fines **educativos y de análisis predictivo de negocio**.  
El dataset es de acceso público a través de Kaggle y debe usarse respetando sus condiciones de uso.

---

Desarrollado como ejercicio de clasificación supervisada aplicada a retención de clientes en telecomunicaciones.
EOF

## 🧑 Datos Personales

- Autor: Fernando González Laso
- Email: gonzalezlasof@gmail.com
