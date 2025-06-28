# 🧠 Predicción del Riesgo de Deserción Académica

Este proyecto de ciencia de datos tiene como objetivo construir un modelo predictivo capaz de identificar estudiantes con alto riesgo de deserción universitaria, a partir del análisis de sus hábitos diarios, indicadores emocionales, académicos y sociales.

---

## 📌 Objetivos

- Realizar un análisis exploratorio (EDA) del comportamiento y hábitos estudiantiles.
- Preprocesar y limpiar el dataset, tratando valores atípicos, traduciendo categorías y estandarizando variables.
- Aplicar técnicas de selección de variables para reducir dimensionalidad y ruido.
- Entrenar modelos supervisados de clasificación (Regresión Logística y Random Forest).
- Comparar métricas de desempeño y justificar la elección final del modelo.
- Extraer conclusiones con respecto a hipótesis educativas y posibles estrategias de intervención.

---

## 📂 Estructura del proyecto

```
Proyecto_Data_Science_I/
├── Proyecto_Data_Science_I_Falco.ipynb         # Notebook principal con todo el análisis
├── enhanced_student_habits_performance_dataset.csv   # Dataset utilizado
└── README.md                                    # Este documento
```
---

## 🧪 Herramientas y técnicas utilizadas

- **Python** 🐍 (Google Colab)
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Limpieza y transformación de datos
- Codificación de variables categóricas
- Detección y justificación de valores atípicos (outliers)
- Feature selection con `SelectKBest`
- Modelado con:
  - `LogisticRegression`
  - `RandomForestClassifier` + `Pipeline` con `StandardScaler`
- Métricas de evaluación: Accuracy, Precision, Recall, F1-score, Matriz de confusión

---

## 🧾 Resultados destacados

- Ambos modelos alcanzaron un **accuracy del 99%**
- **Random Forest** logró un mejor equilibrio entre precisión y sensibilidad en la clase positiva (riesgo de deserción)
- Las variables más influyentes fueron:
  - `nivel_motivacion`
  - `nivel_estres`
  - `promedio_anterior`

---

## 📈 Conclusión

Este proyecto demuestra cómo una adecuada selección de variables y un buen preprocesamiento pueden potenciar modelos simples pero potentes. Además, destaca la utilidad de técnicas de machine learning para la toma de decisiones en contextos educativos, como la detección temprana de estudiantes en riesgo.

---

## 👨‍💻 Autor

**Lautaro Falco**  
Estudiante de Ciencia de Datos | Explorador de problemas complejos con soluciones simples.  
📫 Contacto: https://www.linkedin.com/in/lautaro-gabriel-falco/
🌐 Portfolio completo: [lautaro-falco.github.io](https://lautaro-falco.github.io/) 

---

🔗 https://colab.research.google.com/drive/1c6zadz27bMvOnrGuhZIONGo6hd-rtayv#scrollTo=TRhmEt5Zi_di
