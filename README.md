# Clustering_on_Country_Dataset

## Project Summery

This project clusters countries based on various development-related indicators. The objective is to identify similar groups of countries using unsupervised learning techniques. It also compares performance across multiple clustering algorithms.


## Dataset Features

Country: Name of the country
child_mort: Death of children under 5 years of age per 1000 live births

exports: Exports of goods and services per capita. Given as %age of the GDP per capita

health: Total health spending per capita. Given as %age of GDP per capita

imports: Imports of goods and services per capita. Given as %age of the GDP per capita

income: Net income per person

inflation: The measurement of the annual growth rate of the Total GDP

life_expec: The average number of years a newborn child would live if the current mortality patterns are to remain the same

total_fer: The number of children that would be born to each woman if the current age-fertility rates stay the same

gdpp: The GDP per capita. Calculated as the Total GDP divided by the total population

## Libraries Used

pandas, numpy, matplotlib, seaborn, sklearn, plotly


## Model Used


The project evaluates and compares four clustering algorithms: KMeans,DBSCAN,Agglomerative Clustering,Mean Shift

It also includes PCA (Principal Component Analysis) for: Dimensionality reduction,Visual comparison of clusters


## Evaluation & Visualization

Cluster visualizations using PCA-reduced 2D plots

Model comparison based on how well clusters are separated

Heatmaps and plots for better interpretability




