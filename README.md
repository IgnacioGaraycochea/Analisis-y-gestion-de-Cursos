# Analisis-y-gestion-de-Cursos
Este proyecto consiste en un panel de control interactivo desarrollado en Power BI para consolidar, analizar y gestionar la información relativa a cursos, inscripciones y rendimiento académico/educativo. 
A partir de un conjunto de datos estructurado en la tabla de datos principal, se procesaron y visualizaron indicadores clave (KPIs) para facilitar el seguimiento de métricas educativas y análisis de cobertura.

Herramientas y Tecnologías Utilizadas

* **Power BI Desktop:** Modelado de datos, estructuración del informe y diseño visual.
* **Power Query:** Limpieza de datos, ajuste de tipos de columna y normalización de la información.
* **DAX (Data Analysis Expressions):** Creación de medidas calculadas para obtener métricas agregadas (total de inscritos, promedios, distribución por categorías, etc.).
* **Fuente de Datos:** Tabla de datos de origen estructurada (`TABLA_CURSOS`).

Detalle General de la Tabla (362 Registros)

A continuación se muestra una vista previa del barrido completo de la tabla procesada. 

![Tabla Cursos Parte 1](./images/tabla-cursos-01.png)
![Tabla Cursos Parte 2](./images/tabla-cursos-02.png)

<details>
<summary>🔍 <b>Haz clic aquí para desplegar las capturas restantes de la tabla completa (Partes 3 a 10)</b></summary>

<br>

![Tabla Cursos Parte 3](./images/tabla-cursos-03.png)
![Tabla Cursos Parte 4](./images/tabla-cursos-04.png)
![Tabla Cursos Parte 5](./images/tabla-cursos-05.png)
![Tabla Cursos Parte 6](./images/tabla-cursos-06.png)
![Tabla Cursos Parte 7](./images/tabla-cursos-07.png)
![Tabla Cursos Parte 8](./images/tabla-cursos-08.png)
![Tabla Cursos Parte 9](./images/tabla-cursos-09.png)
![Tabla Cursos Parte 10](./images/tabla-cursos-10.png)

</details>

---

Métricas e Insights Destacados

A través de los filtros dinámicos e interactivos del tablero, se pueden analizar los siguientes puntos clave:

* **Volumen Total:** Visualización general del total de cursos analizados y su distribución por categoría/estado.
* **Métricas Principales (KPIs):** Indicadores resumidos para un diagnóstico rápido.
* **Segmentación:** Análisis comparativo por área temática, modalidad o nivel.

Estructura del Repositorio

* `images/`: Carpeta con las 10 capturas de pantalla de la tabla completa.
* `TABLA_CURSOS.pbix`: Archivo ejecutable del proyecto en Power BI.
* `README.md`: Documentación principal del repositorio.

Cómo abrir este proyecto

1. Clona o descarga este repositorio en tu computadora.
2. Abre el archivo `TABLA_CURSOS.pbix` directamente con **Power BI Desktop**.
