# 📊 Documentación Dashboard – Looker Studio

Este documento describe los gráficos presentes en el dashboard de **Finanzas Iglesia la Viña**, cuya fuente de datos corresponde a una planilla en **Google Sheets**. El objetivo es dejar claridad sobre el propósito, origen de datos, métricas y lógica de cada visualización.

---

## 🗂️ Información General

* **Herramienta:** Looker Studio
* **Fuente de datos:** Planilla Google Sheets
* **Responsable:** Franco Chamorro
* **Última actualización:** 16-01-2026

---

## 🧩 Estructura del Dashboard

El dashboard se compone de los siguientes gráficos:

1. Gráfico 1 – *Recaudación por concepto de "DIEZMO Y OFRENDA"*
2. Gráfico 2 – *Recaudación por concepto de "EDUCA MONTEALTO"*
3. Gráfico 3 – *Recaudación por concepto de "CENTRO MEDICO"*
4. Gráfico 4 – *Recaudación por concepto de "ACOGE"*
5. Gráfico 5 – *Detalle por mes de "DIEZMO Y OFRENDA", "EDUCA MONTEALTO", "CENTRO MEDICO" y "ACOGE"*
6. Gráfico 6 – *Detalle por mes y semana de "DIEZMO Y OFRENDA"*
7. Gráfico 7 – *Detalle "DIEZMO Y OFRENDA" por reunión*
8. Gráfico 8 – *Detalle "DIEZMO Y OFRENDA" por concepto horario (AM/PM)*
9. Gráfico 9 – *Detalle "DIEZMO Y OFRENDA" por mes*4
10. Gráfico 10 – *"DIEZMO Y OFRENDA": Actual vs Año Pasado*
11. Gráfico 10 – *Recaudación Total "DIEZMO Y OFRENDA" por mes y semana*

---

## 📈 Gráfico 1 – *Recaudación por concepto de "DIEZMO Y OFRENDA"*

![Gráfico 1](./imagenes/grafico_1.png)

### 🎯 Objetivo

*Este gráfico tiene como objetivo mostrar el total recaudado por concepto de diezmo y ofrenda durante el mes en curso, junto con el porcentaje de cumplimiento de la meta mensual, establecida por el pastor para dicho concepto. Permite visualizar de forma clara tanto el monto total recaudado en el mes como el nivel de avance respecto a la meta definida.* 

### 📊 Tipo de visualización

*MEDIDOR*

### 🗃️ Fuente de datos

* Google Sheets: *Planilla Finanzas*

### 📐 Dimensiones

* *Categoría: DIEZMO;OFRENDA*
* *Organización: Organización Social la Viña*

### 🎛️ Filtros aplicados

* *Segmentador de tiempo externo*

### 📝 Observaciones

*Meta es ingresada manualmente por el equipo de finanzas*

---

## 📈 Gráfico 2 – *Recaudación por concepto de "EDUCA MONTEALTO"*

![Gráfico 2](./imagenes/grafico_2.png)

### 🎯 Objetivo

*Este grafico tiene como objetivo mostrar el total recaudado por concepto de "EDUCA MONTEALTO" (COLEGIO) durante el mes en curso, junto con el porcentaje de cumplimiento de la meta mensual, establecida por el pastor para dicho concepto. Permite visualizar de forma clara tanto el monto total recaudado en el mes como el nivel de avance respecto a la meta definida*

### 📊 Tipo de visualización

*MEDIDOR*

### 🗃️ Fuente de datos

* Google Sheets: *Planilla Finanzas*

### 📐 Dimensiones

* *Categoría: EDUCA MONTEALTO*
* *Organización: Organización Social la Viña*

### 🎛️ Filtros aplicados

* *Segmentador de tiempo externo*

### 📝 Observaciones

*Meta es ingresada manualmente por el equipo de finanzas*

---

## 📈 Gráfico 3 – *Recaudación por concepto de "CENTRO MEDICO"*

![Gráfico 3](./imagenes/grafico_2.png)

### 🎯 Objetivo

*Este grafico tiene como objetivo mostrar el total recaudado por concepto de "CENTRO MEDICO" durante el mes en curso, junto con el porcentaje de cumplimiento de la meta mensual, establecida por el pastor para dicho concepto. Permite visualizar de forma clara tanto el monto total recaudado en el mes como el nivel de avance respecto a la meta definida*

### 📊 Tipo de visualización

*MEDIDOR*

### 🗃️ Fuente de datos

* Google Sheets: *Planilla Finanzas*

### 📐 Dimensiones

* *Categoría: CENTRO MEDICO*
* *Organización: Organización Social la Viña*


### 🎛️ Filtros aplicados

* *Segmentador de tiempo externo*

### 📝 Observaciones

*Meta es ingresada manualmente por el equipo de finanzas*

---

## 📈 Gráfico 4 – *Recaudación por concepto de "ACOGE"*

![Gráfico 4](./imagenes/grafico_2.png)

### 🎯 Objetivo

*Este grafico tiene como objetivo mostrar el total recaudado por concepto de "ACOGE" durante el mes en curso, junto con el porcentaje de cumplimiento de la meta mensual, establecida por el pastor para dicho concepto. Permite visualizar de forma clara tanto el monto total recaudado en el mes como el nivel de avance respecto a la meta definida*

### 📊 Tipo de visualización

*MEDIDOR*

### 🗃️ Fuente de datos

* Google Sheets: *Planilla Finanzas*

### 📐 Dimensiones

* *Categoría: CENTRO MEDICO*
* *Organización: Organización Social la Viña*

### 🎛️ Filtros aplicados

* *Segmentador de tiempo externo*

### 📝 Observaciones

*Meta es ingresada manualmente por el equipo de finanzas*

---

## 📈 Gráfico 5 – *Detalle por mes de "DIEZMO Y OFRENDA", "EDUCA MONTEALTO", "CENTRO MEDICO" y "ACOGE"*

![Gráfico 5](./imagenes/grafico_2.png)

### 🎯 Objetivo

*Este gráfico tiene como objetivo visualizar de forma clara qué categoría presenta la mayor y la menor recaudación por mes, así como el total recaudado mensual de las cuatro categorías. Además, permite analizar el comportamiento mensual de cada categoría, facilitando la identificación de aquellas que aportan mayor recaudación y las que contribuyen en menor medida.*

### 📊 Tipo de visualización

*TABLA*

### 🗃️ Fuente de datos

* Google Sheets: *Planilla Finanzas*

### 📐 Dimensiones

* *Categoría: DIEZMO, OFRENDA, MONTE ALTO, CENTRO MEDICO, ACOGE, FECHA*
* *Organización: Organización Social la Viña*

### 🎛️ Filtros aplicados

* *No Aplica*

### 📝 Observaciones

*1. No resulta sencillo determinar si existieron variaciones positivas o negativas entre las distintas categorías en cada mes.*
*2. Gráfico ordenado de forma descendente*
*3. Gráfico con filas totales*

---
