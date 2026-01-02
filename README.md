# 📊 Proyecto 10 – Análisis de Certificados de Salubridad  
**Stack:** Excel · MySQL · Power BI

## 📝 Descripción
Este proyecto consiste en el análisis de certificados de salubridad emitidos en la ciudad de Chiclayo, utilizando un flujo completo de Business Intelligence.  
Se trabajó con datos reales, previamente normalizados, y se calcularon indicadores clave (KPIs) mediante consultas SQL para posteriormente visualizarlos en Power BI.

El objetivo del proyecto es identificar patrones temporales, categóricos y de proceso que permitan comprender el comportamiento de las solicitudes y certificados emitidos.

---

## 🎯 Objetivos del análisis
- Analizar el volumen total de certificados de salubridad.
- Comparar certificados otorgados entre los años 2024 y 2025.
- Identificar la distribución de certificados por categoría.
- Analizar el tipo de solicitud (renovación vs nuevo).
- Evaluar las etapas del proceso de solicitud.
- Analizar el tipo de empresa solicitante (excluyendo el rubro comercial).
- Identificar los giros de negocio más frecuentes.

---

## 📁 Dataset
- **Fuente:** Archivo Excel con datos normalizados.
- **Registros:** 9,316 certificados.
- **Columnas:** Variables temporales, geográficas, categóricas y de negocio.
- **Estructura:**
  - Hoja 1: Datos completos (raw)
  - Hoja 2: Datos normalizados para análisis

---

## 🛠️ Herramientas utilizadas

### 📌 Excel
- Revisión y validación de datos.
- Normalización de columnas relevantes.
- Almacenamiento de KPIs calculados.

### 📌 MySQL
- Cálculo de KPIs mediante consultas SQL.
- Uso de funciones de agregación (`COUNT`, `GROUP BY`, `ORDER BY`, `WHERE`).
- Análisis temporal y categórico.

### 📌 Power BI
- Construcción de dashboard interactivo.
- Visualización de KPIs.
- Uso de filtros por año, mes y licencia.
- Análisis visual del proceso de certificación.

---

## 📈 KPIs desarrollados
- **KPI 1:** Total de certificados de salubridad.
- **KPI 2:** Certificados otorgados en 2024 vs 2025.
- **KPI 3:** Certificados por categoría.
- **KPI 4:** Solicitudes de petición de certificados.
- **KPI 5:** Etapas de la solicitud.
- **KPI 6:** Tipo de empresa solicitante (excluyendo comercial).
- **KPI 7:** Top 5 giros de negocio (EMPR_GIRO).

---

## 📊 Dashboard
El dashboard en Power BI permite:
- Visualizar el total de certificados emitidos.
- Analizar tendencias por año.
- Identificar categorías y tipos de solicitud predominantes.
- Evaluar el estado y flujo de las solicitudes.
- Analizar los giros de negocio más frecuentes.

---

## 🧠 Conclusiones generales
- La mayor parte de los certificados corresponde a solicitudes de renovación.
- La categoría D concentra la mayor cantidad de certificados.
- El año 2025 presenta un mayor número de certificados en comparación con 2024.
- El rubro de servicios domina entre los tipos de empresa solicitante.
- Restaurantes, bodegas y boticas son los giros más frecuentes.

---

## 🚀 Autor
**Joseph Farid Rojas Manrique**  
Analista de Datos  
Especialización en Excel, SQL y Power BI  

---

## 📌 Nota
Este proyecto forma parte del portafolio personal de análisis de datos y demuestra el uso integrado de herramientas de Business Intelligence para la toma de decisiones.
