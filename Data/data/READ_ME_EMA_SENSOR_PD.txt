READ ME

Habets, Jeroen; Kubben, Pieter, 2020, "EMA and wearable sensor monitoring in PD", https://doi.org/10.34894/5HHK8H, DataverseNL.

# Please cite data descriptor when using data.

WEARABLE SENSOR DATA

# Folders per patient

Sensor files are organised in folders per patient. Folders have patient ID’s as name ’110001’, ’110002’, etc until ’110021’ (’110012’ is correctly missing).

# Filenames for sensor location and timestamp

## First part filename: Sensorlocation_

File names start with sensor code.
left sensors = ['13797', '13799', '13794', '13806']
right sensors = ['13805', '13801', '13793', '13795']
chest sensors = ['13804', '13792', '13803', '13796']

## Second part filename: date

Date in format _yyyymmdd_

## Last part filename: time

Time in format hhmmss.

# Every filename is the starting timestamp of the file. Every file is recorded with 200 Hz sample frequency.

# Sensors recorded when not charging. When recording period passed 00.00, a new file was created.

# For example code how to extract and analyse the elf-files, see GitHub / jgvhabets / sensor_EMA_PD_monitoring.

# Explanation about EMA data xlsx file attached to Dataverse repository.

# For further questions: j.habets@maastrichtuniversity.nl, or jgvhabets@gmail.com

 