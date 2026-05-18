# 🌶️ Cuadro de Mando — Mercado de las Especias (Power BI)

## 📌 Problema de negocio

Un negocio de venta de especias con presencia en 6 países europeos y más de 4.500 pedidos anuales necesita responder preguntas clave para tomar decisiones: ¿Qué productos generan más beneficio real? ¿Qué segmento de cliente es más rentable? ¿En qué meses caen las ventas y por qué?

Sin un sistema de análisis centralizado, estas preguntas se responden tarde, mal o con Excel manual.

## 🎯 Objetivo

Diseñar un cuadro de mando ejecutivo interactivo en Power BI que permita al equipo directivo monitorizar ventas, rentabilidad y rendimiento operativo en tiempo real, con capacidad de filtrado por año, mes, categoría y segmento.

## 📊 Dataset

- **Fuente:** Kaggle
- **Período:** 2024–2025
- **Volumen:** 4.500 pedidos, 29.000 unidades, 6 países
- **Estructura:** Modelo estrella con tablas de hechos y dimensiones

## 🔧 Proceso técnico

| Fase | Descripción |
|------|-------------|
| Extracción | Importación de ficheros CSV desde Kaggle |
| Transformación | Limpieza y modelado con Power Query Editor |
| Modelado | Modelo estrella: tabla de hechos de ventas + dimensiones |
| Cálculos | Medidas DAX: Ventas Netas, Beneficio, Margen %, YoY, MoM, Ticket Medio |
| Visualización | Dashboard de 6 páginas con navegación interactiva |

## 📋 Páginas del dashboard

| Página | Contenido |
|--------|-----------|
| Resumen Ejecutivo | KPIs globales + tendencia de ventas + mapa geográfico |
| Rendimiento Temporal | Evolución mensual, comparativa trimestral, indicadores YoY y MoM |
| Producto y Categoría | Mix de ventas, rentabilidad por producto, volumen vs margen |
| Clientes y Países | Segmentación por tipo de cliente, contribución por país |
| Puestos y Región | Rendimiento operativo por puesto y familia de productos |
| Storytelling | Insights accionables con recomendaciones de negocio |

## ✅ Resultados y métricas del negocio

| KPI | Valor |
|-----|-------|
| Ventas Netas totales | 197.820 € |
| Beneficio total | 98.830 € |
| Margen global | 49,96% |
| Pedidos | 4.500 |
| Ticket Medio | 43,96 € |
| País principal | España (69,37% de ventas) |
| Categoría más rentable | Especias (58.000 € ventas) |
| Producto top por beneficio | Pesto |

## 💼 Valor para el negocio

El dashboard permite al equipo directivo identificar los productos y categorías que concentran el beneficio, detectar meses con caída de ventas y activar medidas correctoras, comparar el rendimiento de puestos y regiones, y segmentar clientes para priorizar acciones comerciales.

## 🛠️ Stack tecnológico

`Power BI Desktop` `Power Query` `DAX` `Modelo Estrella` `CSV`

## 📁 Estructura del repositorio

- README.md
- data/ → archivos CSV fuente
- report/ → Reto1_Especias.pbix
- docs/ → Documentacion_Reto1.docx, Presentacion_Reto1.pptx, Dashboard_Preview.pdf

## 🔮 Líneas de mejora futuras

- Conectar a Power BI Service para actualización automática
- Incorporar análisis de estacionalidad con series temporales
- Añadir página de previsión de demanda por producto
