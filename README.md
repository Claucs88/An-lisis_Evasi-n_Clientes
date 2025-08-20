
#  **Predicción de Cancelación de Clientes (Churn) – Telecom X**

##  Descripción
Este proyecto tiene como objetivo predecir la **cancelación de clientes (Churn)** en una empresa de telecomunicaciones.  
Se construyó un **pipeline de Machine Learning** que incluye preprocesamiento, entrenamiento y evaluación de modelos, junto con un análisis de los factores que más influyen en la cancelación.

---

##  Objetivos del proyecto
- Preparar y limpiar los datos (tratamiento, codificación, normalización).
- Balancear las clases con **SMOTE** para mejorar la detección de clientes en riesgo.
- Entrenar y comparar **dos modelos de clasificación**:
  - **Regresión Logística** (requiere normalización).
  - **Random Forest** (robusto sin normalización).
- Evaluar el rendimiento con métricas: **Accuracy, Precision, Recall, F1-score y Matriz de Confusión**.
- Analizar la **importancia de las variables** y proponer **estrategias de retención** basadas en los resultados.

---

##  Tecnologías utilizadas
- Python 3.x  
- Pandas, Numpy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Matplotlib, Seaborn  
- Joblib (para exportar modelos)  

---

##  Resultados principales
- **Regresión Logística**: Accuracy = 82.8%, desempeño balanceado, útil como modelo interpretable.
- **Random Forest**: Accuracy = 84.4%, mejor recall en clientes que cancelan → modelo recomendado para despliegue.
- **Factores de mayor riesgo de churn**:
  - Método de pago: *Electronic check*.
  - Planes con **cargos altos** (mensuales/totales).
  - **Clientes nuevos** con contratos cortos.
  - Servicio de internet: *Fiber optic*.
- **Factores protectores**:
  - Contratos largos (anual/bianual).
  - Servicios adicionales: *Tech Support, Online Security, Backup*.
  - Paquetes y múltiples líneas.

---

##  Estrategias de retención propuestas
1. Incentivar el cambio de método de pago (de *Electronic check* a opciones automáticas).
2. Ofertas personalizadas para clientes con **altos cargos**.
3. **Onboarding proactivo** en los primeros 90 días para nuevos clientes.
4. Promover **servicios adicionales y paquetes** como mecanismo de fidelización.
5. Beneficios por permanencia (descuentos, upgrades escalonados).


---

##  Autora
Proyecto desarrollado por **Claudia Correa**, Ingeniera Comercial
**Linkedin:** [https://www.linkedin.com/in/claudia-correa-sanchez/]  

