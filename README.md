 
# Predicción de Concentraciones de PM2.5 en Ecuador

Este proyecto desarrolla modelos estadísticos de series temporales (ARIMA y SARIMA) para predecir los niveles futuros de PM2.5 en las provincias de Pichincha y Azuay, utilizando datos históricos del Ministerio del Ambiente, Agua y Transición Ecológica del Ecuador.

## 📊 Datos

- **Fuente**: Portal de Datos Abiertos del Gobierno del Ecuador  
- **Archivo usado**: `concentracionpm25.csv`  
- **Contenido**: Concentraciones históricas de PM2.5 registradas por estaciones automáticas de monitoreo ambiental.

---

## 🧪 Modelos utilizados

- **ARIMA**: Para series sin estacionalidad fuerte.  
- **SARIMA**: Para series con patrones estacionales.  

Se usaron métricas como MAE, RMSE y R² para validar los resultados.

---

## ⚙️ Requisitos

Antes de ejecutar el notebook, asegúrate de tener instalado Python 3.7+ y las siguientes librerías:

```bash
pip install pandas matplotlib numpy scikit-learn statsmodels jupyter
```

---

## 🚀 Ejecución del código

1. **Clona el repositorio:**

```bash
git clone https://github.com/AlyssaCadena/ProyectoMBDCapstone.git
cd proyecto-pm25
```

2. **Activa un entorno virtual (opcional pero recomendado):**

```bash
python -m venv venv
source venv/bin/activate    # En Linux/macOS
venv\Scripts\activate.bat   # En Windows
```

3. **Instala los requerimientos:**

```bash
pip install -r requirements.txt
```

> Si no tienes el archivo `requirements.txt`, puedes crearlo con:

```bash
pip freeze > requirements.txt
```

4. **Ejecuta el Jupyter Notebook:**

```bash
jupyter notebook ProyectoCapstone_AlyssaCadena.ipynb
```

---

## ✅ Resultados esperados

- Visualizaciones de las series temporales de PM2.5 por estación y provincia.
- Predicciones de corto plazo basadas en modelos ARIMA y SARIMA.
- Evaluación del ajuste del modelo mediante métricas estadísticas.
- Discusión sobre la viabilidad del uso de estos modelos en entornos de baja infraestructura computacional.

---

## 📌 Créditos

Desarrollado por **Alyssa Cadena** como parte de un trabajo de titulación de maestría.  
Datos proporcionados por el Ministerio del Ambiente, Agua y Transición Ecológica. (2022). Programa Calidad del Aire. Obtenido de https://www.ambiente.gob.ec/programa-calidad-del-aire-fase-iii/.

---
