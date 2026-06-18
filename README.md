# Predicción de Churn en Telecomunicaciones mediante Machine Learning

## Autor

**Francisca Concha**
Máster en Business Intelligence y Analítica de Datos
Universidad Católica de Valencia (UCV)

---

## Asignatura

Prácticas Aplicadas en Análisis de Datos y Machine Learning

---

## Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un sistema de predicción de churn (abandono de clientes) en el sector de las telecomunicaciones utilizando técnicas de análisis de datos y Machine Learning.

Para ello se integraron múltiples fuentes de información relacionadas con el perfil de los clientes, su comportamiento económico, la interacción con los servicios de soporte y la evolución temporal de diferentes indicadores de negocio.

A lo largo del proyecto se aplicó una metodología completa de ciencia de datos que incluyó análisis exploratorio, limpieza de datos, feature engineering, modelado predictivo y evaluación de resultados.

---

## Objetivos

* Analizar los factores asociados al abandono de clientes.
* Identificar señales tempranas de riesgo de churn.
* Construir variables predictivas basadas en comportamiento histórico.
* Comparar diferentes algoritmos de Machine Learning.
* Seleccionar el modelo con mejor capacidad predictiva.
* Proponer recomendaciones de negocio orientadas a la retención de clientes.

---

## Datos utilizados

El proyecto integra información procedente de distintas fuentes:

* Información demográfica y contractual de clientes.
* Facturación mensual.
* Historial de pagos e impagos.
* Interacciones con soporte.
* Indicadores de calidad del servicio.
* Variable objetivo de churn.

---

## Metodología

El desarrollo del proyecto siguió las siguientes fases:

1. Análisis exploratorio de datos (EDA).
2. Limpieza y preparación de datos.
3. Análisis estadístico.
4. Feature Engineering.
5. Construcción de variables temporales.
6. Entrenamiento de modelos predictivos.
7. Evaluación y comparación de modelos.
8. Interpretación de resultados y conclusiones de negocio.

---

## Modelos evaluados

Se entrenaron y compararon los siguientes algoritmos:

* Logistic Regression
* Random Forest
* Gradient Boosting
* XGBoost

---

## Resultados principales

Los análisis realizados mostraron que las variables más relevantes para la predicción del churn están relacionadas con:

* Retrasos de pago.
* Historial de impagos.
* Antigüedad del cliente.
* Nivel de satisfacción.
* Número de interacciones con soporte.
* Variables temporales derivadas mediante Feature Engineering.

Entre los modelos evaluados, **Gradient Boosting** obtuvo el mejor rendimiento global en términos de capacidad discriminatoria (ROC-AUC), mientras que **Logistic Regression** destacó por su capacidad para identificar clientes con riesgo de abandono mediante un mayor Recall.

---

## Conclusiones

Los resultados obtenidos demuestran que es posible identificar patrones asociados al abandono de clientes utilizando información económica, operativa y relacional.

Las técnicas de Machine Learning permitieron detectar señales tempranas de riesgo y generar información útil para apoyar estrategias de retención de clientes.

Asimismo, el proyecto puso de manifiesto la importancia del Feature Engineering y de la incorporación de variables temporales para representar de forma más precisa la evolución del comportamiento de los clientes.

---

## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* XGBoost
* Jupyter Notebook

---

## Estructura del repositorio

* `data/` → datos utilizados en el proyecto
* `notebooks/` → análisis exploratorio y modelado
* `src/` → código reutilizable
* `models/` → modelos entrenados
* `reports/` → visualizaciones y resultados

---

## Licencia

Proyecto académico desarrollado para fines formativos dentro del Máster en Business Intelligence y Analítica de Datos de la Universidad Católica de Valencia.
