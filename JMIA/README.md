# Regresión lineal de precios de bolsa versaltil de JUMIA

## ¿Que es JUMIA?

Jumia Technologies AG opera una plataforma de comercio electrónico en África, Portugal, Alemania y los Emiratos Árabes Unidos. La plataforma de la compañía consiste en un mercado que conecta a los vendedores con los consumidores; servicio logístico que permite el envío y entrega de paquetes de vendedores a consumidores; y el servicio de pago, que facilita las transacciones a los participantes activos en la plataforma de la empresa en mercados seleccionados. Su mercado ofrece varios productos en una variedad de categorías, como moda y ropa, belleza y cuidado personal, hogar y vida, bienes de consumo de rápido movimiento, teléfonos inteligentes y otros productos electrónicos, así como acceso a diversos servicios, incluida la entrega de alimentos en restaurantes, reservas de hoteles y vuelos, publicidad clasificada, recarga de tiempo aire y entrega instantánea. La compañía se conocía anteriormente como Africa Internet Holding GmbH y cambió su nombre a Jumia Technologies AG en enero de 2019. Jumia Technologies AG fue fundada en 2012 y tiene su sede en Berlín, Alemania.

-------------------
Lo que pretendo en este proyecto personal, es lograr comparar varios metodos de regresión lineal como el basico, ElasticNet y uno robusto como Huber. a partir de los datos proveidos por JUMIA durantes los años 2019,2020,y 2021.
Como pasos preliminares realizamos dos situciones.
* Realizamos la limpieza de los datos, donde logramos observar que no teniamos datos null ni información faltante.
* Un analicis de los precios a largo de los años, donde descubrimos los efectos en la pandemia del COVID 19 en la cotización de precios en la bolsa de valores.

## Data
_Covid data_ extraída de:
- [Kaggle](https://www.kaggle.com/datasets/mohammedouahman/jumia-stock-data-price-updated-all-time)

## Notebooks
Los notebooks están divididos entre los datos de covid y educación siguiendo este patrón:
1) Limpieza
2) Analisis y Exploración
3) Modelo

## Project organization

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks. Naming convention: number (for ordering),
│   ├── 0. extraction     topic, delimited description, e.g.
│   ├── 1. Limpieza        
│   ├── 2. Analisis y Exploración
│   └── 3. Modelo
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment.
```