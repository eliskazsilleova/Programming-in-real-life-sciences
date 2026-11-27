# How many individual genes can be linked to distinct congenital heart diseases? 

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation and Usage](#installation-and-Usage)
- [Data Interpretation](#data-interpretation)
- [Contact](#contact)

## Description
In this project, dataset from Wikidata, based on the specific SPARQL input, was used. It contains congential heart diseases that are linked to number of gene defects.  
It was built with the intention to educate and show connections in cardiology. 

## Features
- **SPARQL Query**: Pulling data from WikiData in a form of a table
- **D3.js**: Turning data into visual bar chart through d3.rollups() 
- **Interactive opacity**: Ensuring that opacity changes when mouse enters/leaves the area of a bar with fucntions "mouseenter" and "mouseleave"

## Installation and Usage
The website can be easily opened through the url found in the repository, in the section "About". Therefore, no installation is needed.

## Data Interpretation 
After the bar chart is displayed, several congenital heart diseases are visible, linked to a number of associated genes. In the usual scenario, majority of diseases are linked to only one gene. What is important to remember, is that the SPARQL query takes data from live data base that can change constantly and therefore no primary interpretation is possible. It is more of an easily accessible tool for quick representation, connecting number of genes to congenital heart diseases. 
In the SPARQL, the "congenital heart disease" term was filtered from the data, as the research was centered around the individual heart diseases found in newborns. That is why subclass was rather used in the SPARQL template, and not the deeper subclass which would be indicated by *. The reason is, that deeper subclass was showing unnecessary connections and polluted the graph. The project aimed to show the data straightforwardly.  
This graph functions as an easily accesible tool for quick representation, connecting number of genes to congenital heart diseases. 

## Contact
To report bugs, provide feedback or ask any questions, contact me through an university email e.zsilleova@student.maastrichtuniversity.nl
