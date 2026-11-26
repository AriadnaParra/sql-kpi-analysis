# Análisis de desempeño financiero con SQL

Proyecto del bootcamp de Análisis de Datos de TripleTen (Sprint 3). Exploración de KPIs de negocio mediante consultas SQL, con entrega en un resumen ejecutivo.

## Objetivo

Extraer y analizar indicadores clave de desempeño financiero (ventas vs. meta mensual, percentiles de distribución) a partir de una base de datos relacional, usando SQL como herramienta principal de análisis.

## Qué se hizo

- **Consultas SQL**: extracción de métricas de ventas mensuales, comparación contra metas (`monthly_target`) y cálculo de percentiles de distribución (`Upper_percentile`, `Lower_percentile`, `Upper_Limit`, `Lower_Limit`) para detectar meses atípicos.
- **Selección de periodo**: lógica para analizar un mes específico (`Selected_Month`) dentro del rango de datos disponible.
- **Dashboard**: panel resumen con los indicadores financieros calculados.

## Herramientas

SQL (consultas de agregación y análisis estadístico) + Google Sheets para la presentación del resumen ejecutivo.

## Resultado

Proyecto evaluado y **aprobado** por el equipo de revisión de TripleTen.

## Archivo

`proyecto.xlsx` — hojas: `Dashboard`, `monthly_target`, `Selected_Month`, `Lower_percentile`, `Upper_Limit`, `Lower_Limit`, `Upper_percentile`.

---
*Proyecto desarrollado por Ariadna Parra como parte del programa Data Analyst de [TripleTen](https://tripleten.com).*
