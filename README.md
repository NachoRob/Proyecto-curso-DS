# 🚢 Titanic - Data Science Bootcamp Project  

## 📌 Descripción  
Este proyecto forma parte del bootcamp de Data Science y tiene como **objetivo principal aplicar todas las técnicas aprendidas** en el curso. Se basa en el análisis del famoso dataset del **Titanic**, utilizando herramientas de **exploración de datos, preprocesamiento, modelado y ajuste de hiperparámetros** para predecir la **supervivencia de los pasajeros**.  

📊 **Metodología utilizada:** Se sigue la metodología **CRISP-DM**, que guía el flujo de trabajo de ciencia de datos en seis etapas:  

---

## 🏆 **1️⃣ Comprensión del Negocio**
- **Objetivo del análisis:**  
  Predecir la **probabilidad de supervivencia de los pasajeros** del Titanic en función de sus características personales y del viaje.  
- **Justificación:**  
  Este análisis permite desarrollar habilidades en **exploración de datos, limpieza, transformación y modelado predictivo**, esenciales en Data Science.  
- **Hipótesis:**  
  Factores como **el género, la edad y la clase del pasajero** pueden influir significativamente en la probabilidad de supervivencia.  

---

## 🔍 **2️⃣ Comprensión de los Datos**
- **Fuente:** Dataset público del Titanic en Kaggle.  
- **Descripción de las variables principales:**  
  - `Survived`: 1 = sobrevivió, 0 = no sobrevivió.  
  - `Pclass`: Clase del pasajero (1ª, 2ª, 3ª).  
  - `Sex`: Género del pasajero.  
  - `Age`: Edad del pasajero.  
  - `Fare`: Precio del boleto.  
  - `Embarked`: Puerto de embarque.  

🔹 **Análisis Exploratorio de Datos (EDA)**  
✔ Distribución de variables clave.  
✔ Correlación entre variables.  
✔ Visualización de outliers y valores faltantes.  

---

## 🛠 **3️⃣ Preparación de los Datos**
- **Limpieza y tratamiento de valores nulos.**  
- **Transformaciones de datos:**  
  ✔ **One-Hot Encoding** para variables categóricas (`Sex`, `Embarked`).  
  ✔ **Escalado con StandardScaler** para mejorar el rendimiento de los modelos.  
- **Feature Engineering:**  
  ✔ Creación de nuevas variables (`Title` extraído de `Name`).  
  ✔ **Reducción de dimensionalidad con PCA** para mejorar eficiencia.  

---

## 🤖 **4️⃣ Modelado**
Se probaron diferentes modelos de Machine Learning:  
✅ **Regresión Logística** 📈  
✅ **K-Nearest Neighbors (KNN)** 🔍  
✅ **Random Forest Classifier** 🌲  

✔ **Optimización de hiperparámetros con `GridSearchCV`**.  
✔ **Validación cruzada para evaluar rendimiento de modelos**.  

---

## 📊 **5️⃣ Evaluación**
**Métricas utilizadas:** (Estándar en este proyecto)  
✔ **Precisión (Precision)**  
✔ **Recall**  
✔ **F1-score**  
✔ **AUC-ROC**  

🔹 **Resultados principales:**  
✔ **Random Forest** fue el modelo con mejor desempeño.  
✔ **PCA ayudó a reducir la dimensionalidad sin afectar mucho el rendimiento.**  
✔ **GridSearchCV permitió encontrar los mejores hiperparámetros** para cada modelo.  

---

## 🚀 **6️⃣ Implementación**
- **El modelo final se guardó para predicciones futuras.**  
- **Se documentaron mejoras potenciales:**  
  ✔ Probar modelos más avanzados como XGBoost.  
  ✔ Refinar la imputación de valores nulos.  
  ✔ Evaluar la importancia de más features.  

---

## 📂 **Estructura del Proyecto**
```
📂 Titanic-Project
│── 📂 data
│   ├── train.csv
│   ├── test.csv
│── 📂 notebooks
│   ├── 1_EDA.ipynb
│   ├── 2_Preprocesamiento.ipynb
│   ├── 3_Modelado.ipynb
│── 📂 models
│   ├── best_model.pkl  # Modelo entrenado guardado
│── 📂 reports
│   ├── CRISP_DM_Titanic_Report.md  # Documento con la estructura CRISP-DM
│── README.md
│── requirements.txt
│── main.py  # Script para hacer predicciones
```

---

## 🎯 **Cómo Usar este Proyecto**
Si deseas replicar el análisis y entrenar los modelos, sigue estos pasos:

1️⃣ **Clonar el repositorio:**  
```bash
git clone https://github.com/NachoRob/Titanic-Project.git
cd Titanic-Project
```
2️⃣ **Instalar dependencias:**  
```bash
pip install -r requirements.txt
```
3️⃣ **Ejecutar los notebooks:**  
```bash
jupyter notebook
```

---

## 📬 **Contacto**
📧 Email: ignaciorob86@gmail.com  
📸 Instagram: i_ro_86  
🐦 Twitter (X): @Ignacio83743803  

💡 **¡Cualquier sugerencia o feedback es bienvenido!** 🚀

