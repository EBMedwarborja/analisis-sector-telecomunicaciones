# analisis-sector-telecomunicaciones

# 📡 Análisis del Sector de Telecomunicaciones

Este proyecto tiene como objetivo analizar el comportamiento del sector telecomunicaciones, con énfasis en los servicios de **acceso a Internet**, así como otros servicios relacionados como **telefonía fija**, **telefonía móvil**, **televisión**, **portabilidad** y **servicios postales**. El análisis está diseñado para ayudar a una empresa del sector a identificar oportunidades de negocio, comportamientos del mercado y orientar decisiones estratégicas con base en los datos más recientes.

---

## 🎯 Objetivos del Proyecto

- Realizar un análisis exploratorio de los datos del sector telecomunicaciones.
- Detectar patrones de comportamiento por servicio y año.
- Evaluar tendencias de uso y suscripciones a nivel nacional.
- Identificar oportunidades de mejora y expansión del servicio de internet.
- Crear un dashboard interactivo con indicadores clave (KPIs).

---

## 📁 Estructura del Proyecto

proyecto_acceso_internet/ │ ├── data/ # Archivos originales en Excel │ ├── Telefonia_fija.xlsx │ ├── Telefonia_movil.xlsx │ ├── Television.xlsx │ ├── Portabilidad.xlsx │ └── servicios_postales.xlsx │ ├── notebooks/ │ └── EDA_sector_telecom.ipynb # Notebook con el análisis exploratorio │ ├── dashboard/ │ └── dashboard_interactivo.py / .pbix # Visualización interactiva │ ├── docs/ │ └── informe_analisis.md / .pdf # Reporte descriptivo del proyecto │ └── README.md # Documentación del proyecto (este archivo)


---

## 📊 Datasets Analizados

| Archivo                      | Descripción general |
|-----------------------------|---------------------|
| **Telefonia_fija.xlsx**     | Información sobre líneas activas de telefonía fija por operador y año. |
| **Telefonia_movil.xlsx**    | Detalles sobre líneas móviles, segmentadas por tecnología (2G, 3G, 4G, etc.). |
| **Television.xlsx**         | Datos sobre suscriptores a servicios de televisión por cable o satelital. |
| **Portabilidad.xlsx**       | Estadísticas de portabilidad entre operadores móviles. |
| **servicios_postales.xlsx** | Información mensual sobre el uso de servicios postales oficiales y privados. |

---

## 🔎 Análisis Exploratorio de Datos (EDA)

Se desarrolló un análisis profundo sobre cada dataset utilizando Python y librerías como `pandas`, `seaborn` y `matplotlib`.  
Los principales pasos fueron:

- Carga y revisión de datasets.
- Identificación y tratamiento de:
  - **Valores nulos**
  - **Outliers (valores extremos)**
  - **Registros duplicados**
- Exploración de tendencias temporales y estacionales.
- Visualización de comparativas entre tecnologías, operadores y servicios.
- Comentarios analíticos incluidos directamente en el notebook.

---

## 📉 Dashboard Interactivo

Se creó un dashboard que permite explorar los principales indicadores por servicio y año.  
Este incluye:

- Filtros por tipo de servicio, año y operador.
- Visualización de evolución mensual/trimestral.
- KPI principales para cada segmento.
- Interactividad total para facilitar el análisis.

> Herramientas: Power BI / Streamlit

---

## 📌 Requisitos Técnicos

- Python 3.10+
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebook
- (Opcional) Power BI / Streamlit

Instalar dependencias:

```bash
pip install -r requirements.txt

Cómo Ejecutar el Proyecto

    Clona el repositorio:

git clone https://github.com/EBMedwarborja/analisis-sector-telecomunicaciones.git
cd analisis-sector-telecomunicaciones

    Abre el notebook EDA:

jupyter notebook notebooks/EDA_sector_telecom.ipynb

    Ejecuta el dashboard (si aplica):

streamlit run dashboard/dashboard_interactivo.py













