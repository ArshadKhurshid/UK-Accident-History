
# UK Accident

## Supervised Learning

### Project

#### Install

This project requires Python 3.6 and the following Python libraries installed:


```python
NumPy
Pandas
matplotlib
scikit-learn
```

You will also need to have software installed to run and execute an iPython Notebook

We recommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

#### Code

In a terminal or command window, navigate to the top-level project directory capstone_project/ (that contains this README) and run one of the following commands:


```python
ipython notebook UKAccident.ipynb
```

or


```python
jupyter notebook UKAccident.ipynb
```

This will open the iPython Notebook software and project file in your browser.

#### Run

In a terminal or command window, navigate to the top-level project directory capstone_project/ (that contains this README) and run one of the following commands:

#### Data

This data set contains total of 14999 rows and 10 columns. Target variable (left) is imbalance dataset. It contains 3751 records of employee who have left the company. 11428 records of employee who stayed in the company. Here we are trying to predict employee who can quit. Dataset has been extracted from Kaggle.

Dataset Link: https://www.kaggle.com/daveianhickey/2000-16-traffic-flow-england-scotland-wales

#### Features

- Location_Easting_OSGR:
- Location_Northing_OSGR
- Longitude
- Latitude: 
- Police_Force:
- Accident_Severity:
- Number_of_Vehicles
- Number_of_Casualties
- Date
- DateTime
- Day_of_Week
- Time
- Local_Authority_(District)
- Local_Authority_(Highway)
- 1st_Road_Class
- 1st_Road_Number
- Road_Type
- Speed_limit
- Junction_Detail
- Junction_Control
- 2nd_Road_Class
- 2nd_Road_Number
- Pedestrian_Crossing-Human_Control : Was there a human controller and what type?
- Pedestrian_Crossing-Physical_Facilities: Was it a zebra crossing, or bridge, or another type?
- Light_Conditions : Day, night, street lights or not.
- Weather_Conditions : Wind, rain, snow, fog.
- Road_Surface_Conditions : Wet, snow, ice, flood.
- Special_Conditions_at_Site : Was anything broken or defective, e.g. an obscured sign?
- Carriageway_Hazards : Was something in the way, e.g. a pedestrian, another accident, something in the road?
- Urban_or_Rural_Area
- Did_Police_Officer_Attend_Scene_of_Accident : 
- LSOA_of_Accident_Location : 
- Year :


#### Target Variable

- Did_Police_Officer_Attend_Scene_of_Accident (0 - arrived, 1- Did not arrived)
