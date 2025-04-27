# 💳 Creditcard Regresión

## 🎯 Objetivo

- Documentar paso a paso en un notebook.
- Aplicar el proceso SEMMA al dataset `creditcard`.
- Realizar limpieza de datos, análisis exploratorio (EDA) y entrenamiento de 5 modelos de machine learning.
- Evaluar desempeño usando F1-score, AUC y matriz de confusión.
- Extraer conclusiones relevantes basadas en los resultados.

## ✅ Conclusiones

- El análisis evidenció que la regresión lineal sin regularización fue inicialmente adecuada, logrando un R² de 0.94 y un MSE de 4014.09.
- La incorporación de regularización mediante Ridge y Lasso no mejoró significativamente los resultados: en Ridge, los ajustes fueron mínimos, y en Lasso, la penalización excesiva redujo la precisión.
- Los modelos avanzados, especialmente Random Forest, demostraron un rendimiento superior, alcanzando un R² de 0.99 y un MSE de 457, capturando de manera efectiva las relaciones no lineales en los datos.
- Gradient Boosting también mostró mejoras importantes (R² de 0.97), aunque ligeramente inferior a Random Forest.
- Random Forest resultó ser el modelo más preciso para este conjunto de datos, superando ampliamente a los modelos de regresión lineal y regularizada.
