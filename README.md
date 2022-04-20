# PD-Watch-Dashboard
This project creates an interactive visualization dashboard of Parkinson's patient wearable and self-report data to illustrate wearable correlates of Parkinsonian disease symptoms.

In the original study conducted by Jeroen Habits, Parkinson's patients wore acclerometry sensors on their left and right wrists as well as on their chest.  Patients wore these sensors throughout the day and were instructed to fill out a self-report questionaire for their motor and cognitive symptoms throughout the day.  For each questionairre, patients collected at least 15 minutes of wearable data prior to filling out the form.

Data and preprocessing coded created by Jeroen Habits and more info can be found in these links:<br>
Data - https://dataverse.nl/dataset.xhtml?persistentId=doi:10.34894/5HHK8H <br>
Preprocessing Code - https://github.com/jgvhabets/sensor_EMA_PD_monitoring <br>

To create a dashboard, load "Visualize.ipynb" in jupyter notebook and run all.  At the bottom of the notebook file, a locally-hosted link will be created for the dashboard.  The dashboard currently includes 7 different recordings for one patient over 1 day with the following visualizations for each data segment:<br>
1. Time-series of left/right/chest sensor accelerometry and gyroscope
2. Scatter polar plot of patient mood scores
3. Scatter polar plot on cognition assessments
4. Scatter polar of patient-reported symptom severity
5. Data Recording date and time frame
6. Patient-report medication status - eg: ON, OFF, ON turning OFF, OFF turning ON

Sample pic of the current version of the dashboard:
![Screenshot](https://github.com/BobbyWilt/PD-Watch-Dashboard/blob/main/sample/dashboard_2.0.jpg)
