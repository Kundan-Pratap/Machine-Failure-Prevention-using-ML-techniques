Predictive Maintenance for Milling Machines
Overview
This repository contains a Jupyter notebook (predictive_maintenance_milling_machine.ipynb) that explores the AI4I 2020 Predictive Maintenance Dataset. The notebook focuses on data exploration for predictive maintenance in milling machines, including loading the dataset, basic data inspection, and visualization setup using libraries like Pandas, Plotly, and Seaborn.
The dataset simulates various sensor readings from a milling machine, including air temperature, process temperature, rotational speed, torque, tool wear, and failure indicators. The goal is to analyze these features to predict machine failures.
Dataset

Source: The dataset used is ai4i2020.csv, which can be downloaded from UCI Machine Learning Repository or included in the repository.
Features:

Type (categorical: L, M, H)
Air temperature [K]
Process temperature [K]
Rotational speed [rpm]
Torque [Nm]
Tool wear [min]
Machine failure (binary target)
Failure modes: TWF, HDF, PWF, OSF, RNF


Size: 10,000 rows
