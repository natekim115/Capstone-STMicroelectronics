# Capstone-STMicroelectronics

This project was developed in partnership with STMicroelectronics with Python scripts for data processing written and edited as a collective team.
The team consisted of Andy Kwan, Kian Guan Ho, Ruslan Tita, Phillip Ko, and Nathan Kim.

Personal contribution to the scripts:

trim_data - since data collections were done in minute intervals, this function took out the delay between the end of wanted data points and the time to shut off the data collection.

trim_interval_data - cuts certain amount of intervals specified based on the inputted value for the function. For example, if the first two intervals and last three intervals were unwanted in the data file, this function would eliminate those for visualization.

syncrhonize - take data files and cut out the initial unwanted data points by syncing the Qvar sensor data with the acceleration spike used to mark the starting point of data collection.
