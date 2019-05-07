Alexander Hilton
Alex@AlexanderHilton.com


These Jupyter Notebooks are the Python code used for a portion of the SNHU Capstone whichw as an analysis of the Intake and Outcome data provided by the Austin Animal Shelter

The Data comes in from the 1-DataGrab.ipynb file and is stored in the same file location allowing for ease of access.
A word cloud is generated from the 2-DogCloud.ipynb file which can be used in marketing, a simple visualization.
3-APICallLocationData.ipynb contains an API call in order to gather GPS location data on the pickup location of animals, the API is deactivated currently. Some errors were made in this process so the process had to be manually tweaked as errors came up, next time an error exemption will be included.
4-MergeInOut.ipynb merges the Intake Data with the Location data joined to the Outcome Data
5-MachineLearningOutcome.ipynb creates multiple machine learning models using SciKit-Learn in an attempt to predict Outcome from Intake, a Random Forest was finally used to report.
6-MapStrayCatDog-Seasonal.ipynb mapped the pickup locations of animals in order to better understand the trends of animals throughout Austin.
