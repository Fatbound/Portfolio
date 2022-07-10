# Predicción de tipos de trampas petrolíferas en el Golfo de México.

## ¿Que es Oil Play Prediction?

EEUU siempre se ha destacado por la libertad de sus datos de conocimiento público, en esta ocasión dentro de la base de datos BSEE, se descargó una data  que contiene toda la información geológica de las arenas en el golfo de México hasta el año 2019. Esta información fue recolectada mediante la infinidad de pozos perforados en esta zona del mundo. Cabe aclarar, que de esta información recopilada por las perforaciones se obtuvo la información de la trampa petrolífera donde se encontraba entrampado el petróleo.

-------------------
Lo que pretendo en este proyecto personal, es realizar un análisis y la creación de un modelo dentro de la industria petrolera, la cual soy profesional. En esta ocasión, obtenemos los datos de las arenas productivas en el golfo de México mediante más de 10.000 datos de perforaciones a través de los años.
* Análisis de la data original y evolución de la creación de los datos a través de los años.
* Diseño de modelo de clasificación, utilizando modelos clásicos (Tree), RandomForest, AdaBoost .

## Data
data_ extraída de:
- [BSEE](https://www.data.bsee.gov/Main/GandG.aspx)

## Notebooks
Los notebooks están divididos entre:
1) 0. Exploration
2) 1.play_prediction
3) 2. optimizer

## Project organization

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks.
│   ├── 0. Exploration
│   ├── 1. Play_prediction
│   ├── 2. Optimizer
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.
```