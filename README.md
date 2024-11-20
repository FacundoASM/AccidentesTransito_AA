<p align="center">
    <img src="resources\Img\Encabezado.jpg"></img>
</p>

## *Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.*
***Politécnico Malvinas Argentinas.***


## Aprendizaje Automático.
Autor: Salinas Facundo

# **Predicción de ocurrencia de accidentes de tránsito en Tierra del Fuego.**

<p align="left">
    <a href="https://github.com/crmne/cookiecutter-modern-datascience.git">
    <img src="https://img.shields.io/badge/CCMDS-Project%20template-328F97?logo=cookiecutter" />
    </a>
</p>

[link al cookiecutter]: <> (https://github.com/crmne/cookiecutter-modern-datascience.git)

Video explicativo del proyecto.

<p align="left">
    <a href="https://1drv.ms/v/s!AmapDvNaA28hhqY1ZPQSe9WkcoIaHg?e=grfgoH">
    <img src="https://img.shields.io/badge/OneDrive-Link_al_video-black?style=for-the-badge&logo=icloud&logoColor=white&logoSize=auto&labelColor=blue" />
    </a>
</p>

---

*abstract*

# **Predictive Modeling of Traffic Accidents in Tierra del Fuego** - Insights from Geographic, Temporal, and Accident Type Variables

<p align="justify">
This study explores the development of a machine learning model designed to predict traffic accidents in Tierra del Fuego, where harsh environmental conditions significantly affect road safety. The model is trained on historical data from 2009 to 2023, which includes variables such as accident type, geographic area, and seasonal trends. The results suggest that the model can accurately forecast accident occurrence, allowing authorities to anticipate high-risk scenarios and implement preventive measures that may reduce accident frequency and severity. Consequently, this approach could enhance public safety by targeting high-risk areas and times for intervention. By leveraging such predictive capabilities, local agencies would be able to optimize resource allocation and improve road infrastructure planning. The potential benefits of this model are highlighted in its capacity to support safety strategies and reduce accident-related impacts. The study demonstrates the potential benefits of integrating machine learning models into regional safety planning, providing a valuable tool for addressing one of the province’s most pressing public safety challenges. Future research could refine the model further to increase its predictive accuracy.
</p>

# Objetivo del modelo.
<p align="justify">
El objetivo es desarrollar un modelo de Aprendizaje Automático que permita predecir la ocurrencia de accidentes de tránsito en la provincia de Tierra del Fuego, basándonos en variables como la zona de ocurrencia (rural o urbana), el tipo de accidente (hecho simple, con lesiones, o mortal), y los factores temporales (mes, año). Este modelo podrá ser utilizado por las autoridades locales para anticiparse a situaciones de riesgo y adoptar medidas preventivas.
</p>

# Relevancia local.
<p align="justify">
Este problema es de suma importancia para Tierra del Fuego, ya que las condiciones climáticas extremas y la geografía de la región aumentan el riesgo de accidentes viales, especialmente en las áreas rurales. La identificación de patrones y factores de riesgo mediante técnicas de Aprendizaje Automático puede ayudar a las autoridades locales a diseñar estrategias de prevención más efectivas. Además, contribuiría a la toma de decisiones en cuanto a inversiones en infraestructura y educación vial.
</p>

# Razones para elegir el problema.
<p align="justify">
Elegí este problema porque tiene un impacto directo en la vida de las personas que residen en la provincia, y porque los accidentes de tránsito son una problemática prevenible si se cuentan con los datos y análisis correctos. Además, la disponibilidad de un dataset extenso y detallado sobre los accidentes en la región nos brinda una excelente oportunidad para aplicar técnicas de modelado predictivo y análisis de datos.integrador para mejorar la salud poblacional.
</p>

# Pregunta a responder.

¿Es posible pronosticar la ocurrencia de accidentes en la ciudad de Rio Grande?

---

# Dataset
<p align="left">
    <a href="https://ipiec.tierradelfuego.gob.ar">
    <img src="https://img.shields.io/badge/Link_WEB_IPIEC-FFA500?style=for-the-badge&logo=Google-chrome&logoColor=white" alt="Link WEB IPIEC" />
  </a>
</p>

El dataset que utilizaré fué obtenido del sitio web del IPIEC, el cual es un centro de datos. Esta base de datos específica contiene información de accidentes de tránsito en Tierra del Fuego desde enero de 2009 hasta 2023, con cobertura geográfica en las localidades de Ushuaia, Río Grande, Tolhuin, y un total provincial. Las variables principales incluyen:

1. Accidentes de tránsito (hechos): Colisiones o incidentes en vías públicas o privadas.

2. Víctimas en accidentes de tránsito: Cantidad de muertes en ocasión de accidente de tránsito.

3. Lesionados en accidentes de tránsito: Cantidad de personas que han sufrido lesiones físicas como consecuencia de un accidente.

4. Hechos por zona de ocurrencia: Clasificación de los accidentes en zonas urbanas o rurales.

La base de datos es mensual y cuenta con una cobertura temporal de 14 años, lo que garantiza una amplia cantidad de instancias y una buena representatividad para entrenar y evaluar modelos predictivos.

La data del proyecto está dividida en 3 segmentos principales:

- **0_raw:** Contiene la base de datos original sin modificar

- **1_iterim:** Contiene el dataset organizado en forma de dataframe, solo los hechos en Rio Grande.

- **2_processed:** Contiene el dataset ya limpio para la implementación del modelo

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


## Requisitos de Instalación

1. Python 3.8+
2. Dependencias:
```bash
pip install -r requirements.txt
```

## Dependencias Principales

pandas==2.0.0
numpy==1.24.3
scikit-learn==1.2.2
matplotlib==3.7.1
seaborn==0.12.2

## Uso Rápido

### 1. Clona el repositorio
```bash
git clone https://github.com/[usuario]/accidentes_tierra_fuego.git
cd accidentes_tierra_fuego
```

### 2. Crea y activa el entorno virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate     # Windows
```

### 3. Instala dependencias
```bash
pip install -r requirements.txt
```

# Ejemplo de uso del modelo.
```bash
import pickle

# Cargar modelo
with open('models/modelo_final_accidentes.pkl', 'rb') as f:
    modelo_info = pickle.load(f)
modelo = modelo_info['modelo']
features = modelo_info['features']

# Datos de ejemplo
datos_ejemplo = {
    'Año': 2024,
    'Mes': 7,
    'HechosMortales': 0,
    'HechosConLesiones': 9,
    'Lesionados': 25,
    'HechosRurales': 1
}

# Realizar predicción
prediccion = modelo.predict(X_pred)
```
# Métricas del Modelo

>- R2 Score: 0.86
>- RMSE: 45.63
>- MAE: 35.59

# Contribuciones
Pull requests son bienvenidos. Para cambios mayores, por favor abra un issue primero.

# Licencia
MIT