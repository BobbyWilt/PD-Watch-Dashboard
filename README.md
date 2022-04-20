# PD-Watch-Dashboard
Creates a visualization dashboard of Parkinson's patient wearable and self-report data.

Data and preprocessing coded created by Jeroen Habits and more info can be found in these links:<br>
Data - https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/5HHK8H <br>
Preprocessing Code - https://github.com/jgvhabets/sensor_EMA_PD_monitoring <br>

This project is currently in early stages whereby the dashboard layout and plot styles are still under construction.  To create a dashboard, load "Visualize.ipynb" in jupyter notebook and run all.  At the bottom of the notebook file, a locally-hosted link will be created for the dashboard.  The dashboard currently includes 7 different recordings for one patient with the following visualizations for each data segment:<br>
1. Time-series of left/right/chest sensor accelerometry and gyroscope
2. Scatter polar plot of patient mood scores
3. Scatter polar plot on cognition assessments
4. Scatter polar of patient-reported symptom severity

Sample pic of an early version of the dashboard:
![Screenshot](https://github.com/BobbyWilt/PD-Watch-Dashboard/blob/main/sample/dashboard_2.0.jpg)
