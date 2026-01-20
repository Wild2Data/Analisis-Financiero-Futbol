# ⚽ Análisis Financiero y de Mercado en el Fútbol

Proyecto de **análisis financiero y económico del fútbol**, enfocado en el mercado de fichajes, valoración de jugadores y desempeño económico de los clubes, utilizando visualización de datos para apoyar la toma de decisiones estratégicas.

---

## 🎯 Objetivo del proyecto

Analizar el comportamiento financiero del fútbol profesional para responder preguntas clave como:

- ¿Qué clubes invierten más en fichajes y con qué resultados?
- ¿Cómo se relaciona el gasto en transferencias con el rendimiento deportivo?
- ¿Qué ligas y equipos concentran mayor valor de mercado?
- ¿Existen patrones de sobrevaloración o subvaloración de jugadores?
- ¿Cómo evoluciona el mercado de fichajes a lo largo del tiempo?

---

## ⚽ Contexto del análisis

- Industria: Fútbol profesional
- Enfoque: Finanzas deportivas y mercado de transferencias
- Nivel de análisis:
  - Clubes
  - Ligas
  - Jugadores
- Periodo analizado: Múltiples temporadas (según dataset)

Este proyecto se plantea desde una **perspectiva de negocio**, entendiendo al fútbol como una industria donde las decisiones financieras impactan directamente en el rendimiento y la sostenibilidad de los clubes.

---

### 🏗️ Arquitectura de Datos y Modelo Relacional



Para garantizar la precisión en el análisis de rentabilidad y eficiencia de los fichajes, diseñé una estructura de datos robusta que permite cruzar métricas financieras con resultados deportivos de múltiples ligas.



![Modelo de Datos - Fútbol](https://github.com/Wild2Data/Analisis-Financiero-Futbol/blob/main/images/README/Modelo%20Relacional%20Futbol.png?raw=true)



#### Especificaciones Técnicas del Modelo:

* **Arquitectura:** Esquema en **Estrella (Star Schema)** enfocado en la optimización de medidas DAX complejas.

* **Tabla de Hechos:** Centralizada en los movimientos del mercado de fichajes e inversión salarial para asegurar una granularidad fina por jugador y club.

* **Dimensiones Clave:** Implementación de dimensiones de **Ligas**, **Clubes**, **Temporadas** y **Resultados**, permitiendo filtros cruzados dinámicos sin pérdida de integridad referencial.

* **Normalización:** Proceso de limpieza y estructuración de datos para estandarizar valores de mercado y monedas entre diferentes contextos competitivos.



*Este diseño asegura que el dashboard sea escalable y que los cálculos de ROI (Retorno de Inversión) se ejecuten con alta velocidad de procesamiento.*

---

## 🧠 Enfoque analítico

El análisis se centra en:

- Evaluación de inversiones en fichajes
- Comparación entre gasto y resultados deportivos
- Análisis de valor de mercado de jugadores
- Identificación de tendencias financieras por liga y club
- Visualización clara para usuarios no técnicos

---

## 📊 Principales análisis incluidos

### Finanzas de clubes
- Gasto total en fichajes
- Ingresos estimados
- Balance entre inversión y rendimiento
- Comparación entre clubes

### Mercado de jugadores
- Valor de mercado por posición
- Evolución del valor de jugadores
- Jugadores más caros por temporada
- Relación edad – valor de mercado

### Análisis por ligas
- Ligas con mayor inversión
- Distribución del gasto por país
- Comparación entre ligas top y emergentes

---

## 🛠️ Herramientas utilizadas

- **Excel**
  - Dataset base
  - Limpieza y validación de datos

- **Power BI**
  - Modelado de datos
  - Creación de medidas
  - Dashboards interactivos
  - Visualizaciones financieras y comparativas

> ⚠️ Nota:  
> Este proyecto **no utiliza SQL**, ya que el análisis se realizó directamente sobre datasets estructurados en Excel.

---

## 📈 Dashboards

El proyecto incluye dashboards enfocados en:

- Visión financiera general del mercado
- Comparación de clubes y ligas
- Análisis de fichajes y valor de mercado
- Tendencias temporales del fútbol como industria

🔗 **Ver dashboard en Power BI / NovyPro:**  
*([ANALISIS FINANCIERO FUTBOL](https://app.powerbi.com/view?r=eyJrIjoiYWUwYjc3MzItZmY3YS00M2Y0LWE4MjEtYTZkNTI5MjA0YTRlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9))*

---


---

## 📌 Conclusiones generales

- El mayor gasto en fichajes no siempre garantiza mejor rendimiento deportivo.
- Existen clubes con alta eficiencia financiera frente a otros con sobreinversión.
- El valor de mercado de los jugadores está fuertemente influenciado por edad, posición y liga.
- El fútbol moderno funciona como una industria financiera altamente competitiva.

---

### 🛠️ Tecnologías y Metadatos
![SQL](https://img.shields.io/badge/SQL-Expert-blue) ![Power BI](https://img.shields.io/badge/Power_BI-Advanced-yellow) ![License](https://img.shields.io/badge/License-MIT-green)

**Keywords:** Finanzas Deportivas, ROI, Análisis de Fichajes, Modelado de Datos, ETL.

---

## 👤 Autor

**Williams Alberto Aguilera León**  
Analista de Inteligencia de Negocios y Datos  

🔗 LinkedIn: https://www.linkedin.com/in/williams-alberto-aguilera-león  
---

Este proyecto forma parte de mi portafolio profesional enfocado en **análisis financiero, Business Intelligence y visualización de datos aplicados a industrias reales**.

