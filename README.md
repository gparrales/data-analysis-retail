# Data Analysis Retail

## 📖 Descripción / Overview

Este proyecto analiza el perfil de clientes y su comportamiento de compra mediante técnicas de Análisis Exploratorio de Datos (EDA), limpieza y preparación de datos, con el objetivo de generar información estratégica para apoyar la toma de decisiones comerciales.

A partir de un dataset de más de **2.200 clientes**, se desarrolló un proceso completo de preprocesamiento, análisis estadístico y visualización en **Power BI**, permitiendo identificar patrones de consumo, segmentos de clientes de alto valor y el perfil del buyer persona actual. :contentReference[oaicite:0]{index=0}

---

# Problema de negocio

Una empresa buscaba comprender el comportamiento de compra de sus clientes para responder preguntas estratégicas relacionadas con el consumo, el perfil de sus mejores clientes y la relación entre variables demográficas, económicas y de comportamiento.

El objetivo principal fue transformar los datos históricos en información accionable que permita optimizar futuras estrategias comerciales y de marketing. 

---

# Conjunto de datos

El dataset contiene **2.205 registros y 39 variables** con información relacionada a:

- Información demográfica
- Estado civil
- Nivel educativo
- Ingresos anuales
- Número de hijos
- Antigüedad como cliente
- Compras por diferentes canales
- Gasto por categoría de producto
- Visitas al sitio web
- Respuesta a campañas de marketing

---

# Objetivos del proyecto

- Realizar el proceso de limpieza y transformación de datos.
- Detectar inconsistencias y valores atípicos.
- Comparar diferentes métodos de imputación.
- Construir un dataset preparado para análisis.
- Identificar el perfil del **Buyer Persona**.
- Analizar el comportamiento de compra de los clientes.
- Construir indicadores de negocio (KPI).
- Diseñar un dashboard interactivo en Power BI para la toma de decisiones. :contentReference[oaicite:4]{index=4}

---

# Limpieza y preparación de datos

Durante la etapa de preprocesamiento se realizaron las siguientes actividades:

- Conversión de variables monetarias almacenadas como texto a formato numérico.
- Eliminación del símbolo "$" para permitir análisis estadísticos.
- Identificación y análisis de valores atípicos mediante el método del rango intercuartílico (IQR).
- Comparación de dos métodos de tratamiento de outliers:
  - Reemplazo por mediana.
  - Método de **Capping**.
- Reconstrucción de variables categóricas de:
  - Estado civil.
  - Nivel educativo.
- Creación de una nueva variable de gasto total debido a inconsistencias detectadas en el dataset original.
- Eliminación de variables redundantes y no relevantes para el análisis final. :contentReference[oaicite:5]{index=5}

Finalmente se seleccionó el método **Capping** por ofrecer una mejor eliminación de valores extremos en las variables monetarias sin afectar significativamente el comportamiento general del conjunto de datos. 

---

# Análisis exploratorio de datos (EDA)

El análisis exploratorio permitió identificar importantes patrones en el comportamiento de los clientes.

## Hallazgos principales

- La mayoría de clientes tienen entre **40 y 49 años**.
- Predominan hogares sin niños o adolescentes.
- La permanencia promedio de los clientes es de **6 a 7 años**.
- Las compras por internet y en tienda física representan los canales con mayor utilización.
- Cerca del **50 %** de los clientes visita el sitio web entre **6 y 8 veces por mes**.
- Existe una relación positiva entre el ingreso anual y el consumo total.
- El **20 %** de los clientes con mayores ingresos representa aproximadamente el **50 % del consumo total**, aunque los clientes de mayor valor económico no necesariamente pertenecen al segmento de mayores ingresos. 

---

# Visualización y Dashboard

Se desarrolló un dashboard interactivo en **Power BI** que permite responder las principales preguntas del negocio mediante indicadores estratégicos.

El dashboard permite:

- Identificar el Buyer Persona.
- Analizar el consumo por categoría de producto.
- Comparar consumo por nivel educativo.
- Evaluar el efecto del número de hijos sobre el consumo de productos premium.
- Analizar la relación entre ingresos y consumo.
- Explorar patrones de compra mediante visualizaciones interactivas. 

---

# Conclusiones de negocio

A partir del análisis realizado se identificaron las siguientes oportunidades:

- Priorizar campañas dirigidas al perfil del Buyer Persona identificado.
- Implementar campañas de fidelización para clientes con educación universitaria.
- Desarrollar estrategias enfocadas en clientes con uno o dos hijos, quienes presentan mayor consumo de productos premium.
- Potenciar acciones comerciales orientadas a clientes con ingresos medios-altos, debido a su alta contribución económica.
- Aprovechar el canal web como uno de los principales medios de interacción con los clientes. 

---

# Informe

El repositorio incluye dos informes, técnico y resumen ejecutivo, donde se documenta detalladamente el proceso de análisis, incluyendo:

- Exploración inicial de datos (EDA)
- Limpieza y transformación
- Tratamiento de valores atípicos
- Reconstrucción de variables
- Construcción de indicadores (KPI)
- Desarrollo del dashboard en Power BI
- Insights de negocio
- Recomendaciones finales. 

---

# Estructura del proyecto

```
Data/
│
├── Raw/
├── Processed/
│
Notebooks/
│
├── Data Cleaning.ipynb
├── EDA.ipynb
│
Power BI/
│
├── Dashboard.pbix
│
Documents/
│
├── Informe_Ejecutivo.pdf
├── Informe_Tecnico.pdf
│
Images/
│
├── Dashboard.png
│
README.md
requirements

# Autor

**José Gabriel Parrales Gutiérrez**
**Data Analyst | BI Consultant** 
