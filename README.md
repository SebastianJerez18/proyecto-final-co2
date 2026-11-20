# Proyecto final: emisiones de CO₂ per cápita (Our World in Data)

**Actividad 4 · Proyecto final del curso**

Análisis de datos de emisiones de CO₂ de [Our World in Data](https://ourworldindata.org/co2-emissions) con limpieza, visualización y regresión lineal, para responder:

> ¿Cuánto de las emisiones de CO₂ per cápita de un país se explica por su consumo de energía per cápita y por su PIB per cápita?

## Integrantes

| Integrante | Usuario GitHub | Responsabilidad |
|---|---|---|
| Juan Sebastian Gómez Jerez | SebastianJerez18 | Notebook 01: carga y limpieza |
| Julian Esteban Bravo Daza | JulianBravo1501 | Notebook 02: visualización |
| Ana Maria Villamil Camelo | anamariavillamilcamelo-ux | Notebook 03: modelos y conclusiones |

## Estructura

```text
proyecto-co2/
├── README.md
├── requirements.txt
├── data/
│   ├── owid-co2-data.csv        # dataset original de Our World in Data
│   └── co2_limpio_2019.csv      # salida del notebook 01
└── notebooks/
    ├── 01_limpieza_datos.ipynb
    ├── 02_visualizacion.ipynb
    └── 03_modelo_regresion.ipynb
```

## Cómo ejecutarlo

Los notebooks se ejecutan **en orden** (el 01 genera el archivo que usan el 02 y el 03).

```bash
pip install -r requirements.txt
jupyter notebook
```

## Flujo de trabajo

Cada integrante trabaja en su propia rama (`notebook-nombre`), hace commits pequeños y entrega con un Pull Request revisado por otro integrante.

## Fuente de los datos

- Ritchie, H., & Roser, M. (2020). *CO₂ emissions*. Our World in Data. https://ourworldindata.org/co2-emissions
- Dataset: https://github.com/owid/co2-data
