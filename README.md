<p align="center">
    <img src="resources\Img\Encabezado.jpg">Encabezado</img>
</p>
## *Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.*
***Politécnico Malvinas Argentinas.***


## Aprendizaje Automático.
Autor: Salinas Facundo
# Predicción de ocurrencia de accidentes de tránsito en Tierra del Fuego.
Video explicativo del proyecto.
(LINK)

---

# Objetivo del modelo.
El objetivo es desarrollar un modelo de Aprendizaje Automático que permita predecir la ocurrencia de accidentes de tránsito en la provincia de Tierra del Fuego, basándonos en variables como la zona de ocurrencia (rural o urbana), el tipo de accidente (hecho simple, con lesiones, o mortal), y los factores temporales (mes, año). Este modelo podrá ser utilizado por las autoridades locales para anticiparse a situaciones de riesgo y adoptar medidas preventivas.

# Relevancia local.
Este problema es de suma importancia para Tierra del Fuego, ya que las condiciones climáticas extremas y la geografía de la región aumentan el riesgo de accidentes viales, especialmente en las áreas rurales. La identificación de patrones y factores de riesgo mediante técnicas de Aprendizaje Automático puede ayudar a las autoridades locales a diseñar estrategias de prevención más efectivas. Además, contribuiría a la toma de decisiones en cuanto a inversiones en infraestructura y educación vial.

# Razones para elegir el problema.
Elegí este problema porque tiene un impacto directo en la vida de las personas que residen en la provincia, y porque los accidentes de tránsito son una problemática prevenible si se cuentan con los datos y análisis correctos. Además, la disponibilidad de un dataset extenso y detallado sobre los accidentes en la región nos brinda una excelente oportunidad para aplicar técnicas de modelado predictivo y análisis de datos.integrador para mejorar la salud poblacional.

---

# Dataset
<p align="left">
    <a href="https://ipiec.tierradelfuego.gob.ar">
    <img src="https://img.shields.io/badge/Link_WEB_IPIEC-FFA500?style=for-the-badge&logo=Google-chrome&logoColor=white" alt="Link WEB IPIEC" />
  </a>
</p>

El dataset que utilizaré contiene información de accidentes de tránsito en Tierra del Fuego desde enero de 2009 hasta 2023, con cobertura geográfica en las localidades de Ushuaia, Río Grande, Tolhuin, y un total provincial. Las variables principales incluyen:

1. Accidentes de tránsito (hechos): Colisiones o incidentes en vías públicas o privadas.

2. Víctimas en accidentes de tránsito: Cantidad de muertes en ocasión de accidente de tránsito.

3. Lesionados en accidentes de tránsito: Cantidad de personas que han sufrido lesiones físicas como consecuencia de un accidente.

4. Hechos por zona de ocurrencia: Clasificación de los accidentes en zonas urbanas o rurales.

La base de datos es mensual y cuenta con una cobertura temporal de 14 años, lo que garantiza una amplia cantidad de instancias y una buena representatividad para entrenar y evaluar modelos predictivos.

# Lenguajes y herramientas
<div id="header" align="left">
<img src="https://img.shields.io/badge/Cookiecutter-D4AA00?style=for-the-badge&logo=Cookiecutter&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
</a>
<img src="https://img.shields.io/badge/Microsoft_Excel_CSV-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
</a> 
<img src="https://img.shields.io/badge/machine learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</a>
<img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" />
</a> 
</div>

---

# Organización del proyecto

    ├── LICENSE
    ├── requiremets.txt    <- Archivo con los requerimientos (Librerías) necesarios.
    ├── README.md          <- Acerca del proyecto.
    ├── .gitignore         <- Archivo git para ignorar las librerías en .venv.
    ├── data
    │   ├── 1_interim      <- Base de datos en proceso de limpeza.
    │   ├── 2_processed    <- Base de datos procesada
    │   └── 0_raw          <- Base de datos original.
    │
    ├── docs               <- Documentación del proyecto.
    │
    ├── models             <- Modelo de aprendizaje automático.
    │
    ├── notebooks          <- Jupyter notebooks del procedimiento y ejemplo (3 notebooks).
    │
    ├── venv               <- Ambiente virtual.
    │
    └── resorces           <- Archivos para la presentación.