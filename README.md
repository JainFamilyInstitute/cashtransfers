# Data Visualization: Cash Transfer Documents 

scripts and data visualization for visualizing documents about cash transfers by type and effect.

### 1. data/data.csv
this is the original data source supplied by sidhya and gary

### 2. document_categorization.ipynb and data_structure.ipynb
Recoding of document categories into dummy variables is done through document_categorization.ipynb, resulting in data/data_modified.csv

Breakout of documents into unique rows possessing only one effect and structuring of data into json format is done in data_structure.ipynb, resulting in data/data.json

## script.js
d3.js force layout that intakes the data/data.json file with two levels of parent nodes: 1) by category and 2) by effect.

## index.html
root page that can be used to embed the visualization in iframes
