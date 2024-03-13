# Algeria Forest Fire Detection ML Project
### Overview
This project aims to develop a machine learning model to detect and predict forest fires in Algeria using satellite imagery data. The model utilizes various machine learning algorithms to analyze historical and real-time satellite data to identify patterns and predict potential fire outbreaks.

<!-- ![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png) -->


To run flask application 

```
python application.py
```

Data Set Information:

The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.

122 instances for each region.

The period from June 2012 to September 2012.
The dataset includes 11 attribues and 1 output attribue (class)
The 244 instances have been classified into fire(138 classes) and not fire (106 classes) classes.

### Usage



* To replicate the results of this project, follow these steps:

* Clone this repository to your local machine.

* Install the required dependencies listed in the requirements.txt file.

* Run the Jupyter notebooks in the notebooks directory sequentially to preprocess the data, train the model, and evaluate its performance.

* Customize the model parameters and features as needed for your specific use case.

* Deploy the trained model using the provided deployment scripts or integrate it into your existing system.


Attribute Information:

1. Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012)
Weather data observations
2. Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42
3. RH : Relative Humidity in %: 21 to 90
4. Ws :Wind speed in km/h: 6 to 29
5. Rain: total day in mm: 0 to 16.8
FWI Components
6. Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5
7. Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9
8. Drought Code (DC) index from the FWI system: 7 to 220.4
9. Initial Spread Index (ISI) index from the FWI system: 0 to 18.5
10. Buildup Index (BUI) index from the FWI system: 1.1 to 68
11. Fire Weather Index (FWI) Index: 0 to 31.1
12. Classes: two classes, namely Fire and not Fire