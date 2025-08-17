# Predictive Maintenance for Milling Machines

## Overview
This repository contains a Jupyter notebook [`predictive_maintenance_milling_machine.ipynb`](predictive_maintenance_milling_machine.ipynb) that explores the **AI4I 2020 Predictive Maintenance Dataset**. The notebook focuses on **data exploration** for predictive maintenance in milling machines, including:

- Loading the dataset  
- Basic data inspection  
- Visualization setup using **Pandas**, **Plotly**, and **Seaborn**  

The dataset simulates various sensor readings from a milling machine, including air temperature, process temperature, rotational speed, torque, tool wear, and failure indicators. The goal is to analyze these features to **predict machine failures**.

## Dataset
- **Source:** `ai4i2020.csv` (can be downloaded from the UCI Machine Learning Repository or included in this repository)  
- **Size:** 10,000 rows  

### Features
- `Type` (categorical: L, M, H)  
- `Air temperature` [K]  
- `Process temperature` [K]  
- `Rotational speed` [rpm]  
- `Torque` [Nm]  
- `Tool wear` [min]  
- `Machine failure` (binary target)  
- **Failure modes:** TWF, HDF, PWF, OSF, RNF
