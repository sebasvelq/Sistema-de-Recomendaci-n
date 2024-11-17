# Sistema de Recomendación - SVD

Este proyecto consiste en utilizar la data de **MovieLens ml-100k** 📊 para predecir calificaciones de usuarios a películas. 

## Descripción del Modelo
El modelo inicial **SVD** se utilizó con parámetros predeterminados por el modelo. Las métricas de rendimiento arrojaron los siguientes resultados:
- **RMSE**: 0.9377
- **MAE**: 0.7350

Posteriormente, se implementó **GridSearchCV** para optimizar hiperparámetros como `n_factors` y `reg_all`. Esto permitió una leve mejora en las métricas:
- **RMSE** reducido a 0.9140
- **MAE** a 0.7180

Además, se observó una distribución de calificaciones estimadas con:
- **Media**: 3.53
- **Desviación Estándar**: 0.64

Los errores residuales están distribuidos cerca del cero, con valores extremos entre **3.77** y **-3.63** 🔄. Esto destaca una mejor capacidad de ajuste sin sobreentrenamiento 🚀.

## 📈 Análisis de Gráficas
- La distribución de calificaciones muestra valores concentrados cerca del promedio 📊.
- Los errores predichos son menores en películas y usuarios con más calificaciones, según el heatmap 🌡️.
- Los usuarios activos califican entre **20** y **737** ítems.
- Las películas más populares tienen hasta **583** calificaciones, lo que genera un sesgo hacia el contenido más frecuente 🎥.

## 💡 Posibles Mejoras
1. Usar modelos avanzados como **SVD++** para analizar relaciones más complejas.
2. Ajustar dinámicamente los hiperparámetros según usuarios/ítems.
3. Incorporar **Deep Learning** 🤖, como:
   - Modelos basados en embeddings (**Neural Collaborative Filtering** o **Deep Autoencoders**), para analizar relaciones no lineales complejas entre usuarios e ítems y mejorar el rendimiento del modelo.

---

Contribuciones y sugerencias son bienvenidas. ¡Gracias por revisar este proyecto! 🚀
