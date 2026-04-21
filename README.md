# CIVE 202 Project 4- NRI & Alternative Risk Analysis for Idaho and Montana
Authors: 
Bryce Ripley, Nick Meier

This repository contains the full workflow, all datasets, code, and outputs for the comparative risk analysis of Idaho and Montana using FEMA's National Risk Index (NRI) as well as a custom created risk defention. The project compares both county level and censis tract level risk patterms as well as indcluding social vulnerabilities, a communities resilience, and expected annual lossses on bar charts and maps.

# Project Overview
The goal of this project is to compare FEMAS's risk defention with our own risk defnetion to see how included bais can shift a communites risk score. The two states involved in this comparison analysis are:
* Idaho
* Montana

The process of the workflow is as follows:
* Cleaning and merging the NRI, SVI and shapefiles
* Creating an alternative risk defenition
* Normalize the risk defenition
* Create coutny level bar chart
* Create census tract risk maos
* Interpret the differences in each

# Data Sources
* FEMA National Risk Index
* CDC Soacial Vulnerability Index
* US shapefiles


# How to Run the Notebook
1. Download the .ipynb located int he repository
2. Make sure all data files are downloaded adn stored in the same folder
3. Open notebook adn run all cells from top to bottom
4. As you will see, the notebook will have all loaded datasets as well as the clenaed ones
5.   An alternative risk defention
6.   County Level bar charts
7.   Census tract maps
8.   Exports

# Alternative Risk Defenition
Our alternative risk defeniton was defines as Risk ($) = EAL_VALT × RPL_THEMES × (1 – (RESL_SCORE)/100)
By using this equation, a communities risk will go up if theri expected annual loss is high, thier social vulnerability is high, and or resilience is low. All variables are implemented so the equation gives higher or lower risk based off the severity of the inputted variables.

# Final Outputs of this Workflow
County Level Plots
Census Tract Maps
ALl cleaned and formatted .csv files that were created and analyzed.








