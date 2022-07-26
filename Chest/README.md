# Predicción del tipo de Cancer en torax.

## ¿Que es Chest CT-Scan images Dataset?

Chest CT-Scan images Dataset, es un recopilatorio de imágenes diagnósticas del tórax de ciento de personas en las cuales se le diagnosticó algún tipo de cáncer de Tórax.  A continuación mencionó las clases incluidas en este repositorio.

* Adenocarcinoma
Es la forma más común de cáncer de pulmón representa el 30 por ciento de todos los casos en general y alrededor del 40 por ciento
de todos los casos de cáncer de pulmón de células no pequeñas. 

* Large cell carcinoma
El cáncer de pulmón de carcinoma indiferenciado de células grandes crece y se disemina rápidamente y se puede encontrar en cualquier parte del pulmón. Este tipo de cáncer de pulmón generalmente representa del 10 al 15 por ciento de todos los casos de NSCLC.

* Squamous cell carcinoma
Este tipo de cáncer de pulmón se encuentra centralmente en el pulmón, donde los bronquios más grandes unen la tráquea al pulmón,o en una de las ramas principales de las vías respiratorias. El cáncer de pulmón de células escamosas es responsable de aproximadamente el 30 por ciento de todos los cánceres de pulmón de células no pequeñas, y generalmente está relacionado con el tabaquismo.

-------------------
Lo que pretendo en este proyecto personal, es practicar la implementación de redes neuronales profundas, que me permitan adquirir mayor conocimiento en este rubro que está tomando impulso a nivel mundial. Por otro lado, implemento una red neuronal pre entrenada como DenseNet la cual aporto de manera significativa a mi modelo para obtener un óptimo resultado. 
* Creación de una red neuronal Convolucional desde 0 para la identificación de tipos de cáncer en el tórax y pulmón.
* Implementación de una red neuronal pre entrenada para la optimización de Accuracy y función de perdida de mis datos.

## Data
data_ extraída de:
- [Kaggle](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)

## Notebooks
Los notebooks están divididos entre:
1) 0. Intro
2) 1. First-model
3) 2. pretrained-model-dnsenet

## Project organization

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks.
│   ├── 0. intro
│   ├── 1. First-model
│   ├── 2. pretrained-model-dnsenet
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.
```