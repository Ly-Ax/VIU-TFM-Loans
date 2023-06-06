<img align="right" src="images/viu_cabecera.webp" width="230px">

# <br> Máster en Inteligencia Artificial <br><br>

## TFM: Comparación de Algoritmos de DL frente a Algoritmos de ML Clásicos <br> Caso: Aprobación de Préstamos de la U.S. Small Business Administration (SBA)

[**Alex Castro Gumiel**](https://www.linkedin.com/in/alex-castro-gumiel/)

### Conjunto de Datos

https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied

> Contexto

El conjunto de datos es de la Administración de Pequeñas Empresas de EE.UU. (SBA). La SBA de EE.UU. se fundó en 1953 con el principio de promover y ayudar a las pequeñas empresas en el mercado crediticio de EE.UU. Las pequeñas empresas han sido una fuente principal de creación de empleo en los Estados Unidos; por lo tanto, fomentar la formación y el crecimiento de pequeñas empresas tiene beneficios sociales al crear oportunidades laborales y reducir el desempleo.

Ha habido muchas historias de éxito de empresas emergentes que recibieron garantías de préstamos de la SBA, como FedEx y Apple Computer. Sin embargo, también ha habido historias de pequeñas empresas y/o nuevas empresas que han incumplido con sus préstamos garantizados por la SBA.

> Tarjeta de Datos

Contiene 899164 instancias y 27 variables.

[Diccionario de Datos](data/map/data_dictionary.csv)

[Descripción de los dos primeros dígitos del NAICS](data/map/data_naics.csv)

Conjunto de datos original: "Should This Loan be Approved or Denied?”: A Large Dataset with Class Assignment Guidelines", por: Min Li, Amy Mickel & Stanley Taylor.

Enlace al artículo: https://doi.org/10.1080/10691898.2018.1434342

### Estructura del Proyecto

    ├── data
        ├── clean
        ├── map
            ├── data_dictionary.csv -> Diccionario de Datos
            ├── data_naics.csv -> Descripción de dígitos NAICS
        ├── raw
            ├── sba_national.csv -> Dataset original [DVC - GCP]
    ├── docs
        ├── sba_guidelines_en.pdf -> Articulo original (Inglés)
        ├── sba_guidelines_es.pdf -> Articulo traducido (Español)
    ├── images
        ├── viu_cabecera.webp -> Logotipo de la VIU para cabeceras
    ├── models
    ├── notebooks
        ├── data_exploration.ipynb -> Análisis de Datos Exploratorio
    ├── src
        ├── classifier
        ├── load
        ├── train
        ├── transform

    ├── .gitignore
    ├── LICENSE
    ├── README.md
    ├── requirements.txt
