# Mexico 2012 Election Audit: Crowdsourced vs. Official Data
### `mx2012-crowdsourced-vs-official-election-audit`

*[Leer en Español](#español)*

This repository contains a statistical and exploratory analysis of the 2012 Mexican presidential election results. The project conducts a data audit by comparing two primary information sources:

1.  **Official Data:** District-level results from the National Electoral Institute (**INE**), Mexico's autonomous public authority responsible for organizing elections.
2.  **Crowdsourced Data:** Vote tally sheets (*sábanas*) collected by **#YOSOY132**, a student movement that organized a massive crowdsourced audit by photographing results directly at polling stations.

## 🎯 Project Objective

The main goal is to evaluate the reliability and representativeness of the citizen-gathered dataset. Using data science techniques, we aim to identify sampling biases and determine if the crowdsourced data is statistically sufficient to validate or refute the official results.

## 📊 Results & Conclusions

The analysis yields critical insights regarding data distribution and the quality of the citizen sampling.

### Bias due to Mexico City over-representation
In this final analysis, a **very marked over-representation of entity 9 (Mexico City)** is observed within the *YOSOY132* dataset. More than a quarter of the data comes from this entity, which introduces a **significant bias** in the results.

To evidence this, results are shown **including** and **excluding** Mexico City in the *YOSOY132* dataset:
*   **Votes including Mexico City:** Stronger leaning towards the left coalition (PRD+PT+MC).
*   **Votes excluding Mexico City:** Results align much closer to the official national trends.

### Conclusions on sampling quality
The *YOSOY132* dataset shows **larger percentage discrepancies in under-represented entities**, where the absolute number of votes is very low. This indicates that the sampling **was not well-segmented** and that the collected data are **neither sufficient nor of the necessary quality** to justify or suggest the existence of electoral fraud.

---

<a name="español"></a>
# Español

Este repositorio contiene un análisis estadístico y exploratorio de los resultados de la elección presidencial de México en 2012. El proyecto compara dos fuentes de información:

1.  **Datos Oficiales:** Resultados del Instituto Nacional Electoral (**INE**).
2.  **Datos Ciudadanos:** "Sábanas" de resultados recolectadas mediante *crowdsourcing* por el movimiento estudiantil **#YOSOY132**.

## 🎯 Objetivo
Evaluar la confiabilidad y representatividad del conjunto de datos ciudadanos para determinar si la información recolectada es estadísticamente suficiente para validar o refutar los resultados oficiales.

## 📊 Conclusiones Principales

### Sesgo por sobre-representación de Ciudad de México
Existe una **sobre-representación muy marcada de la Ciudad de México** dentro del dataset de *YOSOY132* (más de un cuarto de los datos). Esto introduce un sesgo significativo que favorece a la coalición "PRD + MOV + PT". Al excluir la CDMX del análisis, los porcentajes se ajustan más a la tendencia oficial nacional.

### Calidad del muestreo
El análisis muestra mayores discrepancias porcentuales en las entidades con pocos datos (sub-representadas). Se concluye que el muestreo **no estuvo bien segmentado** y los datos **no son suficientes ni tienen la calidad necesaria** para probar un fraude electoral sistemático.

---

## 🛠 Tech Stack / Tecnologías
*   **Python 3.10.11**
*   **Matplotlib**
*   **Jupyter Notebooks**
