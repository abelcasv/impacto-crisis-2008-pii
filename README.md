# Impacto Asimétrico de la Crisis de 2008 en la Posición de Inversión Internacional en Europa

Proyecto académico de análisis exploratorio y visualización de datos realizado con **R** y datos de **Eurostat**.

El proyecto estudia la evolución de la Posición de Inversión Internacional de **España, Italia y Alemania** durante el periodo de la crisis financiera de 2008, utilizando técnicas de análisis y visualización de datos.

## Proyecto

[**Ver memoria y proyecto online**](https://abelcasv.github.io/impacto-crisis-2008-pii/)

## Tecnologías

* R
* RStudio
* R Markdown
* Eurostat
* Visualización de datos
* Machine Learning

## Trabajo realizado

* Obtención y preparación de datos procedentes de Eurostat.
* Limpieza y transformación de los datos.
* Análisis exploratorio de la Posición de Inversión Internacional.
* Comparación de la evolución de España, Italia y Alemania.
* Desarrollo de múltiples visualizaciones para identificar tendencias y diferencias.
* Desarrollo de un dashboard interactivo mediante R Markdown.
* Aplicación y comparación de modelos básicos de Machine Learning mediante métricas de evaluación como RMSE.

## Estructura del repositorio

```text
├── R/
│   ├── dashboard.Rmd
│   └── memoria.Rmd
│
├── data/
│   ├── Data_Dashboard.rds
│   ├── Data_Filtered.rds
│   ├── Data_Limpia.rds
│   ├── Data_Trabajo.rds
│   └── geo_countries.geojson
│
└── docs/
    └── memoria.html
```

## Datos

Por motivos de tamaño, no se incluyen en el repositorio algunos datasets intermedios generados durante el proceso de limpieza y transformación:

- `Data_Filtered.rds`
- `Data_Trabajo.rds`

Estos archivos se utilizaron durante el desarrollo del proyecto, pero se han excluido para mantener el repositorio ligero y facilitar su consulta.

El repositorio incluye los scripts, la documentación y los archivos de datos seleccionados utilizados en el análisis.

## Dashboard

El proyecto incluyó un dashboard interactivo desarrollado mediante R Markdown. La versión desplegada originalmente dependía de infraestructura de la universidad y actualmente no se encuentra disponible públicamente.

## Documentación

[Ver memoria completa del proyecto](docs/memoria.html)
