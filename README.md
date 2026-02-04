# 📊 Predicción de Riesgo Crediticio - SVM (Kernel RBF)

Este proyecto desarrolla un modelo predictivo para la clasificación de riesgo bancario, enfocado en identificar clientes con alta probabilidad de incumplimiento.

## 🎯 Resultados del Modelo
El modelo final alcanzó métricas de alto rendimiento, fundamentales para el sector financiero:
* **Accuracy General:** 93.3%
* **Precisión (Riesgo Alto):** 91%
* **Recall / Sensibilidad (Riesgo Alto):** 84% (Capacidad crítica para detectar morosos).

## 🛠️ Stack Técnico y Metodología
* **Algoritmo:** Support Vector Machine (SVM) con **Kernel RBF** para capturar patrones de riesgo no lineales.
* **Preprocesamiento:** Implementación de **RobustScaler** para mitigar el impacto de valores atípicos (outliers) en montos de crédito.
* **Análisis:** Manejo de datos faltantes en cuentas de ahorro y cuenta corriente, transformándolos en categorías de valor predictivo.

## 📈 Visualizaciones Incluidas
En el notebook se incluyen:
1. **Matriz de Confusión:** Validación visual de falsos positivos y negativos.
2. **Fronteras de Decisión:** Representación 2D de cómo el Kernel RBF separa los perfiles de riesgo.

---
*Proyecto desarrollado para demostrar capacidades de análisis de datos y despliegue de modelos de ML.*
<img width="817" height="446" alt="Captura de pantalla (845)" src="https://github.com/user-attachments/assets/5b93d704-4d0b-4020-be37-825d4480fc47" />
