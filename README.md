# PD-Watch-Dashboard - WIP
Creates a visualization dashboard of Parkinson's patient wearable and self-report data.

Data and preprocessing coded created by Jeroen Habits and more info can be found in these links:<br>
Data - https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/5HHK8H <br>
Preprocessing Code - https://github.com/jgvhabets/sensor_EMA_PD_monitoring <br>

This project is currently in early stages whereby I'm still creating plotly visualizations.  These figures will later on be added to a plotly dashboard with interactivity features.  To create a dashboard, load "Visualize.ipynb" in jupyter notebook and run all.  At the bottom of the notebook file, a local link will be created for the dashboard.  The dashboard currently includes 7 different recordings for one patient with the following visualizations for each data segment:<br>
1. Time-series of left/right/chest sensor accelerometry and gyroscope
2. Scatter polar plot of patient mood scores
3. Scatter polar plot on cognition assessments
4. Scatter polar of patient-reported symptom severity
