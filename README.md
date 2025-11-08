# Predicción de Precios de Vuelos con Machine Learning  

## Descripción general  
Este proyecto desarrolla un modelo de **predicción de precios de vuelos** en los segmentos *Economy* y *Business*, aplicando un flujo completo de **Machine Learning supervisado**: desde la exploración inicial de datos (EDA) hasta el modelado y la evaluación final.  

El análisis busca identificar qué variables influyen más en el costo de los vuelos y cómo se puede anticipar el comportamiento del precio con base en información como la aerolínea, el origen, el destino, la duración del vuelo y las escalas.  

Este estudio combina un enfoque **analítico, técnico y de negocio**, orientado a mejorar la comprensión del mercado aéreo y facilitar estrategias de **pricing dinámico** y optimización comercial.  

---

## Flujo metodológico  
El trabajo sigue una estructura reproducible y documentada:  

1. **Exploratory Data Analysis (EDA)**  
   - Limpieza, detección y tratamiento de outliers.  
   - Análisis univariado y bivariado (distribuciones, correlaciones, escalas).  

2. **Ingeniería de características**  
   - Creación de variables temporales (`month`, `day`, `weekday`).  
   - Codificación categórica con *One-Hot Encoding*.  
   - Escalado selectivo de variables numéricas.  

3. **Modelado predictivo**  
   - Comparación de tres algoritmos representativos:  
     - **Ridge Regression** (baseline lineal).  
     - **Random Forest Regressor**.  
     - **Gradient Boosting Regressor**.  
   - Evaluación con métricas MAE, RMSE y R².  

4. **Resultados y conclusiones**  
   - En ambos segmentos, **Random Forest** ofreció el mejor desempeño general:  
     - Economy: R² ≈ 0.87.  
     - Business: R² ≈ 0.85.  
   - Las variables de **duración del vuelo**, **aerolínea** y **origen/destino** mostraron la mayor influencia en el precio.  

---

## Tecnologías utilizadas  

| Herramienta | Uso principal |
|--------------|---------------|
| **Python 3.11+** | Lenguaje de desarrollo principal |
| **Pandas / NumPy** | Limpieza, transformación y análisis de datos |
| **Matplotlib / Seaborn** | Visualización exploratoria y comparativa |
| **Scikit-learn** | Modelado predictivo y evaluación |
| **Jupyter Notebook** | Documentación interactiva del flujo analítico |

---

## Autor  
**Cristián Andrés Galleguillos Vega**  
Biólogo · Máster en Ingeniería en Recursos Naturales · Máster en Data Science & Big Data  
Chile  
[LinkedIn](https://www.linkedin.com/in/cristi%C3%A1n-galleguillos-vega-267343198/)  

---

## Conclusión  
Este proyecto demuestra la aplicación práctica de técnicas de Machine Learning para problemas de **regresión multivariable** en contextos reales de negocio.  
El flujo está diseñado para ser **reproducible, interpretativo y escalable**, sirviendo como base para futuros estudios de predicción de demanda o estrategias de optimización de precios.  
