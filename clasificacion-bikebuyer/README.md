# 🚴‍♂️ Bikebuyer Clasificación

## 🎯 Objetivo

- Documentar paso a paso en un notebook.
- Aplicar el proceso SEMMA al dataset `bikebuyer`.
- Realizar limpieza de datos, análisis exploratorio (EDA) y entrenamiento de 5 modelos de machine learning.
- Evaluar desempeño usando F1-score, AUC y matriz de confusión.
- Extraer conclusiones relevantes basadas en los resultados.

## ✅ Conclusiones

- En términos de **exactitud** y **AUC-ROC**, el **Árbol de Decisión** mostró el mejor rendimiento global, seguido de cerca por el **KNN**, mientras que el **Gradient Boosting** tuvo un rendimiento sólido pero ligeramente inferior.
- El **Árbol de Decisión** se destacó en la identificación de la clase 0 (compradores) y mostró la mejor **sensibilidad**. Sin embargo, el **Gradient Boosting** y **KNN** también demostraron capacidades fuertes en términos de **precisión** y **recall**.
- En general, el **Árbol de Decisión** se posiciona como el modelo más robusto para este conjunto de datos, seguido por **KNN**, mientras que **Gradient Boosting**, aunque efectivo, podría beneficiarse de ajustes adicionales para mejorar la identificación de la clase positiva.
