# Crear el contenido del README.md en formato markdown

readme_content = """# 🌍 Laboratorio: Regresión Lineal y Árboles de Decisión en Calidad del Aire  

Este proyecto forma parte del máster en Inteligencia Artificial y tiene como objetivo aplicar modelos de **regresión lineal simple/múltiple** y **árboles de decisión para regresión**, evaluando su desempeño en el dataset **AirQualityUCI**.  

📚 **Tabla de Contenidos**  
- 🧠 ¿Qué incluye este proyecto?  
- 🔍 Análisis realizado  
- 💻 Tecnologías y librerías utilizadas  
- 🚀 Resultados  
- ⚙️ Cómo ejecutar este proyecto  

---

## 🧠 ¿Qué incluye este proyecto?  
✅ Carga y exploración del dataset **AirQualityUCI.csv**  
✅ Análisis descriptivo de las variables (categóricas y continuas)  
✅ Limpieza de datos: eliminación de columnas innecesarias y valores nulos  
✅ Selección de variable respuesta y predictores  
✅ Entrenamiento de modelos:  
- **Regresión Lineal Simple**  
- **Regresión Lineal Múltiple**  
- **Árboles de Decisión para Regresión**  
✅ Evaluación de modelos con métricas: **MAE, RMSE, R²**  
✅ Visualización de resultados y comparación de desempeño  

---

## 🔍 Análisis realizado  

1. **Carga del dataset**  
   - Se importó el archivo `AirQualityUCI.csv` con `pandas`.  
   - Se verificó el número de instancias y columnas.  

2. **Exploración de datos**  
   - Identificación de variables categóricas (`Date`, `Time`) y continuas (CO, NOx, NMHC, etc.).  
   - Verificación de tipos de datos y rangos.  

3. **Limpieza de datos**  
   - Eliminación de columnas innecesarias (`Unnamed: 15`, `Unnamed: 16`).  
   - Eliminación de valores nulos.  

4. **Selección de variable objetivo**  
   - Variable respuesta: calidad del aire (ej. CO(GT) o contaminantes).  

5. **Modelado**  
   - **Regresión Lineal Simple** con una variable predictora.  
   - **Regresión Lineal Múltiple** con varias variables.  
   - **Árboles de Decisión** ajustados para regresión.  

6. **Evaluación de modelos**  
   - Cálculo de métricas: **MAE, RMSE, R²**.  
   - Comparación de errores para determinar el mejor modelo.  

---

## 💻 Tecnologías y librerías utilizadas  

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🚀 Resultados  

📊 Los modelos permitieron analizar cómo se comportan distintos algoritmos de regresión sobre datos de calidad del aire:  
- La **regresión lineal simple** mostró la relación entre una sola variable predictora y la variable objetivo.  
- La **regresión múltiple** mejoró la capacidad de predicción al incluir más factores.  
- Los **árboles de decisión** capturaron mejor las relaciones no lineales en los datos, aunque con riesgo de overfitting.  

El análisis comparativo evidenció diferencias claras en precisión y capacidad de generalización.  

---

## ⚙️ Cómo ejecutar este proyecto  

1. Clona este repositorio en tu máquina:  
   ```bash
   git clone https://github.com/usuario/RegresionLineal_Arboles.git
