# IDA-2016
Machine Learning challenge to predict the  vehicle has faced the failure due to a specific parts failure or not
# Problem Statement
The task is to come up with a good prediction model for judging whether or not a vehicle faces imminent failure of the specific component or not.
It will help in repairing of the vehical, if we know the part due to which the failure has accored.
# Dataset Description
The dataset consists of data collected from heavy Scania trucks in everyday usage. The system in focus is the Air Pressure system (APS) which generates pressurised air that are utilized in various functions in a truck, such as braking and gear changes. The datasets' positive class consists of component failures for a specific component of the APS system. The negative class consists of trucks with failures for components not related to the APS. The data consists of a subset of all available data, selected by experts. The attribute names of the data have been anonymized for proprietary reasons.
# Real World Objective and Constraints
The cost of a mis-classification can be very high.
No strict latency concerns.
Interpretability is partially important.
Metric : score = 500FN + 10FP
# Data Overview
- Data will be in a file Train.csv 
- Train.csv contains 172 columns:
- Number of rows in Train.csv = 60,000
# Mapping the real world problem to an ML problem
It is a binary classification problem, for the attribute we have to predict wwhether the failure has accoured due to some specific part or not.
