# Data Visualization: Cash Transfer Documents 

scripts and data visualization for visualizing documents about cash transfers by type and effect.

## 1. data/data2.csv
this is the original data source supplied by sidhya and gary

## 2. data/document_categorization.ipynb and data_structure.ipynb > data/data_modified.csv and data/data.json
Recoding of document categories into dummy variables is done through document_categorization.ipynb, resulting in data/data2_modified.csv

Breakout of documents into unique rows possessing only one effect and structuring of data into json format is done in data_structure.ipynb, resulting in data/data_modified.csv and data/data.json

## 3a. script.js
d3.js force layout that intakes the data/data.json file with two levels of parent nodes: 1) by category and 2) by effect.

## 3b. ct.js, taxcredits.js, ubi.js
d3.js force layout that filters data by category on d.cat_recode (cash transfers, tax credits, UBI) and intakes the data/data.json file with one level of parent nodes (effects) 

## 4. index.html, ct.html, taxcredits.html, ubi.html
pages that can be used to embed corresponding visualizations in iframes

## 5. assets
native design file and image files for the icons used in the visualization
