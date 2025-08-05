# ✈️ Loyalty & Flight Data Analysis

> Análisis del comportamiento de clientes dentro de un programa de fidelización de una aerolínea canadiense  
> 📊 Proyecto final del Módulo 3 - Bootcamp adalab Data+ Analyst

---

## 📁 Datos del Proyecto

Este proyecto se basa en el análisis de dos archivos CSV proporcionados por una aerolínea canadiense. A través de limpieza, exploración y visualización, se busca comprender el comportamiento de los clientes dentro de su programa de fidelización.

- `customer_flight_activity.csv` → Actividad de vuelos de clientes
- `customer_loyalty_history.csv` → Perfil de los clientes y detalles de su fidelización
- `info_aerolinea.csv` → Unión de ambos archivos para facilitar el análisis

📂 Los archivos están ubicados en la carpeta [`/files`](./files)

---

## ⚙️ Tecnologías utilizadas

- 🐍 **Python**
- 📦 **Librerías**:
  - `pandas` para manipulación de datos
  - `numpy` para operaciones matemáticas
  - `seaborn` y `matplotlib.pyplot` para visualización

---

## 🧭 Estructura del análisis

El análisis se divide en distintas fases, cada una desarrollada en su notebook correspondiente:

### 1. 🧪 EDA - Actividad de vuelos
Análisis exploratorio del archivo `customer_flight_activity.csv`  
🔗 [`eda_info_vuelos.ipynb`](./eda_info_vuelos.ipynb)

---

### 2. 👥 EDA - Datos de fidelización
Análisis exploratorio del archivo `customer_loyalty_history.csv`  
🔗 [`eda_info_loyalty.ipynb`](./eda_info_loyalty.ipynb)

---

### 3. 🧼 Limpieza y unión de datasets
- Unión de los dos archivos
- Limpieza de duplicados
- Corrección de tipos de datos  
🔗 [`limpieza_union.ipynb`](./limpieza_union.ipynb)

---

### 4. 📊 Visualización de datos combinados
- Gráficos para responder preguntas clave de negocio
- Análisis de patrones por provincias, tipo de tarjeta, educación, etc.  
🔗 [`visualizacion_info_aerolinea.ipynb`](./visualizacion_info_aerolinea.ipynb)

---

### 5. 🧠 Conclusiones y próximos pasos

Este análisis ha permitido responder a las preguntas clave planteadas por la aerolínea, destacando:

- Patrones de temporada alta (junio-agosto)
- Relación positiva entre distancia y puntos
- Distribución desigual por provincias
- Preferencia clara por tarjetas de tipo Star

Además, se proponen próximos pasos como:
- Estudio más profundo del sistema de puntos
- Imputación de salarios nulos
- Validaciones técnicas entre columnas relacionadas

🔗 Consulta el análisis completo en [`conclusiones_y_next_steps.ipynb`](./conclusiones_y_next_steps.ipynb)

---

## 📂 Estructura del repositorio
- ├── files/
- │   ├── customer_flight_activity.csv
- │   ├── customer_loyalty_history.csv
- │   └── info_aerolinea.csv
- ├── 1. README
- ├── 2. eda_info_vuelos.ipynb
- ├── 3. eda_info_loyalty.ipynb
- ├── 4. limpieza_unions.ipynb
- ├── 5. visualizacion_info_aerolinea.ipynb
- ├── 6. conclusiones_y_next_steps.ipynb
- └── README.md
