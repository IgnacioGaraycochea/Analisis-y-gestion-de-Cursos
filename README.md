# Analisis-y-gestion-de-Cursos
Este proyecto consiste en un panel de control interactivo desarrollado en Power BI para consolidar, analizar y gestionar la información relativa a cursos, inscripciones y rendimiento académico/educativo. 
A partir de un conjunto de datos estructurado en la tabla de datos principal, se procesaron y visualizaron indicadores clave (KPIs) para facilitar el seguimiento de métricas educativas y análisis de cobertura.

Herramientas y Tecnologías Utilizadas

* **Power BI Desktop:** Modelado de datos, estructuración del informe y diseño visual.
* **Power Query:** Limpieza de datos, ajuste de tipos de columna y normalización de la información.
* **DAX (Data Analysis Expressions):** Creación de medidas calculadas para obtener métricas agregadas (total de inscritos, promedios, distribución por categorías, etc.).
* **Fuente de Datos:** Tabla de datos de origen estructurada (`TABLA_CURSOS`).

Vista Previa del Dashboard
 (./images/dashboard_cursos.png)

Métricas e Insights Destacados

A través de los filtros dinámicos e interactivos del tablero, se pueden analizar los siguientes puntos clave:

* **Volumen Total:** Visualización general del total de cursos analizados y su distribución por categoría/estado.
* **Métricas Principales (KPIs):** Indicadores resumidos para un diagnóstico rápido.
* **Segmentación:** Análisis comparativo por área temática, modalidad o nivel.

* Estructura del Repositorio

```text
├── data/
│   └── TABLA_CURSOS.csv (o .xlsx)   <-- Dataset original
├── images/
│   └── dashboard_cursos.png         <-- Captura del tablero
├── TABLA_CURSOS.pbix                <-- Archivo del proyecto en Power BI
└── README.md                        <-- Documentación principal
