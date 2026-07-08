# Predicting-F1-Pit-Stops
He escogido el reto de "Predecir Paradas de Autos en carreras de F1" para AFILAR mis habilidades y conocimientos de Machine Learning. 

# 🏎️ Predicting F1 Pit Stops - Kaggle Playground Series (S6E5)

"Desarrollo de un modelo predictivo utilizando XGBoost y técnicas de ensamblado para pronosticar si un piloto entrará a boxes en la siguiente vuelta". (se trabajaron 4 modelos).

## 📊 Resumen del Proyecto y Resultados
* **Métrica Clave:** PR-AUC obtenido de `0.7856` en validación cruzada.
* **Resultado en Kaggle:** Score obtenido 0.85099.

## 🔍 Fases del Desarrollo

### 1. Análisis Exploratorio de Datos (EDA)
* Descubrimientos clave sobre las variables más importantes.
* Manejo de datos sintéticos y desbalance severo de la variable objetivo `PitNextLap`.
* ** 🔗 [Ver Notebook de EDA](./notebooks/EDA_F1_Spit_Stops.ipynb)*

### 2. Estrategia de Modelado y Validación
* **Algoritmos evaluados:** LightGBM, XGBoost, CatBoost y Balanced RF.
* **Validación:** Implementación estricta de **Stratified 5-Fold Cross-Validation** para mitigar el sobreajuste y el *data leakage*.
* ** 🔗 [Ver Notebook de Exploracion](./notebooks/Exploracion_de_modelos_F1_Spit_Stop.ipynb)*

## 🛠️ Tecnologías Utilizadas
* Python, LightGBM, Scikit-Learn, Pandas, Matplotlib/Seaborn, API de Kaggle.
