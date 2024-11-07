# Data Science Project
This is my final project for a 2nd year university data science module.
It uses a CSV file with country panel data

## Project Overview
Using a panel dataset, this project analyses the relationship between GDP and energy consumption across various countries.
The aim is to identify trends and correlations that could inform economic and environmental policy decisions.

## Dataset
- File Name: `GDP_ENERGY.csv`
- Source: [World Bank](https://databank.worldbank.org/source/world-development-indicators)
- Description: Dataset includes yearly records of GDP per capita and measures of energy consumption. Key columns include:
  - Country Name: A country's short-form name
  - Country Code: 3-letter country codes
  - Time: Year of observation
  - GDP per capita, PPP (constant 2017 international $) [NY.GDP.PCAP.PP.KD]
  - Renewable electricity output (% of total electricity output) [EG.ELC.RNEW.ZS]
  - CO2 emissions (metric tons per capita) [EN.ATM.CO2E.PC]
  - Renewable energy consumption (% of total final energy consumption) [EG.FEC.RNEW.ZS]
 
## Project Structure

Here’s a breakdown of the key files in this repository:
- `Project Code.ipynb`: The main Jupyter Notebook that contains the analysis, from data cleaning to final visualizations and interpretations.
- `GDP_ENERGY.csv`: The dataset used in this project.
- `README.md`: This file, provides an overview of the project.

## Requirements
To run the analysis within the Jupyter Notebook, the following libraries are needed:
pandas, matplotlib, numpy, statsmodels
