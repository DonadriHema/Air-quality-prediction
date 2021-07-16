# Air-quality-prediction
Air polution is the world's largest environmental health threat causing 7 million deaths worldwide every year.
It's major constituents are PM2.5,PM10 nad the harmaful green house gases SO2,NO2,CO and other effluents from vehicles and factories affecting not only humans but also other living organisms both in land and sea.
The only effective solution to this global issue is to implememt machine learning algorithms to predict AQI(Air Quality Index)that make people aware of the condition and the govenment also take certain actions on it.
# Install
This project requires Python 3.6 and the following libraries installed:

    NumPy
    Pandas
    matplotlib
    scikit-learn
    seaborn

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
  # Objective
  The  main aim of this project is to predict AQI.
  # Algorithm
  Random Forest regression is used here to predict accurate AQI value.
 Random forest and decision tree predict accurate value(0.98)than linear regression.
 # Code
 The code is provided in Air_AQI.ipynb and the dataset file is present in city_day.csv
 #####
 By using the city dataset (which contain previous year pollutant values related AQI and AQI_BUCKET values)we will train the model and then test by using new values and predict the AQI value.
 By the AQI and AQI_BUCKET values we will know the the quality of air.
 # Dataset Information
 The dataset contains city names,date,the pollutant values PM2.5,PM10,SO2,NO2,CO,NO,NOx,NH3,O3,Benzene,Toluene,Xylene and the output prediction values AQI,AQI_Bucket.
 # Output Variables
 AQI
 AQI_BUCKET
