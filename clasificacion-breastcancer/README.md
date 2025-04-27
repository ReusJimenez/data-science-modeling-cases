# 🧬 Breastcancer Clasificación

## 🎯 Objetivo

- Documentar paso a paso en un notebook.
- Aplicar el proceso SEMMA al dataset `breastcancer`.
- Realizar limpieza de datos, análisis exploratorio (EDA) y entrenamiento de 5 modelos de machine learning.
- Evaluar desempeño usando F1-score, AUC y matriz de confusión.
- Extraer conclusiones relevantes basadas en los resultados.

## ✅ Conclusiones

- Regresión Logística (LR) es el mejor modelo con un promedio de precisión de 0.974936. Este rendimiento indica que LR tiene una alta capacidad para clasificar correctamente los datos en comparación con los otros modelos evaluados. Además, su rendimiento es consistente a lo largo de las diferentes ejecuciones, alcanzando la puntuación perfecta de 1.000 en varias instancias durante la validación cruzada.
- Support Vector Machine (SVM), con una precisión promedio de 0.972436, es también un modelo fuerte y cercano a LR, ofreciendo resultados comparables en muchas ocasiones. Esto lo convierte en una excelente alternativa si se desea explorar un enfoque diferente.
- K-Nearest Neighbors (KNN) muestra un rendimiento sólido con una precisión promedio de 0.962500, pero su variabilidad en los resultados sugiere que puede ser más sensible a la selección de parámetros y requerir un ajuste adicional.
- Naive Bayes y Árboles de Decisión (DT) tienen un rendimiento inferior, con precisiones promedio de 0.939936 y 0.909551, respectivamente. Esto sugiere que estos modelos son menos adecuados para el conjunto de datos en cuestión y podrían no capturar las relaciones en los datos tan efectivamente como LR o SVM.
