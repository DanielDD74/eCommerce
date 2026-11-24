# Customer Churn Analysis | Análisis de abandono de clientes

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)

## 📌 Descripción del proyecto

Proyecto de análisis de datos enfocado en identificar patrones de comportamiento relacionados con el abandono de clientes (*Customer Churn*) en una plataforma de comercio electrónico.

A través de técnicas de análisis exploratorio de datos (EDA), segmentación y visualización, se investigaron diferentes características de los clientes para comprender qué comportamientos están asociados con una mayor tasa de abandono.

## 🎯 Desafío de negocio

El principal desafío consistió en analizar el comportamiento de los clientes para identificar posibles factores relacionados con el abandono de la plataforma.

El objetivo fue encontrar patrones que permitieran detectar segmentos de clientes con mayor riesgo de abandono y generar información útil para apoyar la toma de decisiones y desarrollar estrategias de retención.

## ⚙️ Proceso de análisis

El proyecto se desarrolló mediante las siguientes etapas:

1. **Exploración y preparación de datos**
   - Inspección de la estructura del dataset.
   - Revisión de tipos de datos y valores faltantes.
   - Preparación de las variables para el análisis.

2. **Análisis exploratorio de datos (EDA)**
   - Análisis de la distribución de clientes.
   - Comparación entre clientes que permanecen y clientes que abandonan.
   - Identificación de patrones en el comportamiento de los usuarios.

3. **Análisis de variables**
   - `Login_Frequency`: frecuencia de inicio de sesión.
   - `Membership_Years`: antigüedad del cliente.

4. **Segmentación de clientes**
   - Clasificación de usuarios según su nivel de actividad.
   - Agrupación por antigüedad.
   - Cálculo de tasas de abandono por segmento.

5. **Visualización e interpretación**
   - Gráficas de barras para comparar tasas de abandono.
   - Diagramas de caja (*Boxplots*) para analizar distribuciones.
   - Interpretación de resultados y generación de conclusiones.

## 📊 Principales resultados

### 1. Frecuencia de inicio de sesión vs. abandono

Se identificó una relación inversa entre la frecuencia de inicio de sesión y la tasa de abandono.

| Nivel de actividad | Tasa de abandono |
|---|---:|
| Baja | 36.00% |
| Media-baja | 21.67% |
| Media-alta | 17.79% |
| Alta | 10.62% |

**Hallazgo:** Los clientes con baja actividad presentaron una tasa de abandono aproximadamente 25.38 puntos porcentuales superior a la de los clientes con alta actividad.

### 2. Antigüedad del cliente vs. abandono

Se analizaron cuatro segmentos de clientes según sus años de membresía.

| Antigüedad | Tasa de abandono |
|---|---:|
| Nuevo | 28.64% |
| Intermedio | 28.97% |
| Establecido | 29.08% |
| Antiguo | 28.66% |

**Hallazgo:** Las tasas de abandono fueron muy similares entre los segmentos, por lo que no se identificó una diferencia descriptiva importante relacionada con la antigüedad del cliente.

## 💡 Conclusiones y recomendaciones

- La frecuencia de inicio de sesión mostró una asociación importante con el abandono de clientes.
- Los usuarios con menor actividad podrían representar un segmento prioritario para estrategias de retención.
- La antigüedad de la membresía no mostró diferencias relevantes en las tasas de abandono.
- Se recomienda implementar campañas de reactivación, notificaciones personalizadas y estrategias de participación para usuarios con baja actividad.

Los resultados representan asociaciones estadísticas descriptivas y no demuestran causalidad.

## 🛠️ Herramientas y tecnologías

- **Python:** lenguaje utilizado para el análisis.
- **Pandas:** manipulación, limpieza y transformación de datos.
- **Matplotlib:** creación de visualizaciones.
- **Seaborn:** análisis gráfico y visualización estadística.
- **Jupyter Notebook:** desarrollo y documentación del análisis.

## 📂 Estructura del repositorio

```text
Customer-Churn-Analysis/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── customer_churn_analysis.ipynb
│
├── images/
│   ├── login_frequency_churn.png
│   └── membership_years_churn.png
│
└── README.md
```

## 🚀 Próximas etapas

- Analizar la relación entre `Lifetime_Value` y `Churned`.
- Investigar el impacto de las llamadas a servicio al cliente.
- Evaluar la relación entre el abandono del carrito y el churn.
- Desarrollar un dashboard interactivo en Power BI.
- Proponer estrategias de retención basadas en los hallazgos.

## 👨‍💻 Autor

**Daniel De la Peña**

Junior Data Analyst | Python | SQL | Power BI | Excel

Proyecto desarrollado como parte de mi portafolio de análisis de datos.
