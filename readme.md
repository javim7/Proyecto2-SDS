# Detección de Fraudes en Transacciones Financieras

Este proyecto tiene como objetivo desarrollar y comparar modelos de detección de fraudes en transacciones financieras utilizando técnicas de aprendizaje automático. Se abordan tres enfoques diferentes de reentrenamiento para evaluar su efectividad en entornos cambiantes.

## Modelos Utilizados

Se emplearon dos modelos de aprendizaje automático para la detección de fraudes:

1. XGBoost (Extreme Gradient Boosting)
2. LightGBM (Light Gradient Boosting Machine)

Ambos modelos son ampliamente utilizados en problemas de clasificación y son conocidos por su eficacia y eficiencia en conjuntos de datos grandes y desbalanceados.

## Reentrenamientos

Se exploraron tres enfoques diferentes de reentrenamiento para evaluar su efectividad en la detección de fraudes:

1. Reentrenamiento Total: Todos los datos disponibles se utilizan para reentrenar el modelo periódicamente.
2. Reentrenamiento Semestral: El modelo se reentrena cada seis meses utilizando los datos más recientes.
3. Reentrenamiento Trimestral: El modelo se reentrena cada tres meses utilizando los datos más recientes.

## Conclusiones

- El enfoque de reentrenamiento total se destacó como el más efectivo entre los tres, con un rendimiento generalmente superior y una tendencia positiva en la capacidad de detección de transacciones fraudulentas.
- Entre los modelos utilizados, LightGBM mostró un rendimiento superior en comparación con XGBoost en términos de recall y capacidad para detectar transacciones fraudulentas.

## Autor

Javier Mombiela [GitHub](https://github.com/javim7).
