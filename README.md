# Análisis y modelado del riesgo de impago en tarjetas de crédito

## Descripción

Este proyecto analiza el riesgo de impago de clientes con tarjeta de crédito utilizando técnicas de minería de datos y aprendizaje automático.

El trabajo combina dos enfoques:

- Segmentación de clientes mediante técnicas de clustering.
- Predicción del impago mediante modelos supervisados.

El objetivo es identificar patrones de comportamiento financiero y construir modelos capaces de detectar clientes con mayor probabilidad de incumplimiento de pago.

## Dataset

Se utiliza el conjunto de datos **Default of Credit Card Clients**, disponible en el repositorio UCI Machine Learning Repository.

Características principales:

- 30.000 clientes.
- Información demográfica.
- Historial de retrasos en pagos.
- Facturación mensual.
- Pagos realizados.
- Variable objetivo: impago en el mes siguiente.

## Metodología

El proyecto sigue la metodología CRISP-DM:

1. Comprensión del problema.
2. Comprensión y exploración de los datos.
3. Limpieza y transformación.
4. Reducción de dimensionalidad mediante PCA.
5. Segmentación de clientes.
6. Construcción de modelos predictivos.
7. Evaluación de resultados.

## Técnicas utilizadas

### Análisis exploratorio

- Estadística descriptiva.
- Visualización de distribuciones.
- Matriz de correlaciones.

### Reducción de dimensionalidad

- PCA (Principal Component Analysis).

### Clustering

- K-Means.
- K-Medians.
- PAM.
- K-Means con distancia Manhattan.
- DBSCAN.
- OPTICS.

### Clasificación

- Árbol de decisión.
- Árbol podado.
- Random Forest balanceado.

## Estructura del proyecto

```text
Proyecto/
│
├── data/
│   └── creditcard.xls
│
├── docs/
│   └── Proyecto_Mineria_Datos_Riesgo_Crediticio.pdf
│
├── src/
│   └── analisis.Rmd
│
└── README.md
