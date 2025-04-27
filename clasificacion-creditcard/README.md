# 💳 Creditcard Clasificación

## 🎯 Objetivo

- Documentar paso a paso en un notebook.
- Aplicar el proceso SEMMA al dataset `creditcard`.
- Realizar limpieza de datos, análisis exploratorio (EDA) y entrenamiento de 5 modelos de machine learning.
- Evaluar desempeño usando F1-score, AUC y matriz de confusión.
- Extraer conclusiones relevantes basadas en los resultados.

## ✅ Conclusiones

- La regresión logística y el Random Forest son los modelos más destacados en términos de rendimiento, aunque ambos tienen oportunidades de mejora en la identificación de instancias positivas.
- KNN ofrece un rendimiento aceptable, pero su capacidad de detección es inferior. El SVM, a pesar de su alto AUC-ROC, enfrenta desafíos significativos en la identificación de instancias positivas, mientras que el árbol de decisión presenta un desempeño razonable pero con un riesgo de sobreajuste.
- Se resalta la importancia de considerar no solo la precisión general, sino también el equilibrio entre precisión y recall al evaluar la efectividad de los modelos.
