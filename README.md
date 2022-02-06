## <center> Climate Change Analysis using Deep Learning</center>
**<center>Rohan Takey <center>**
<center>rohantakey246@gmail.com</center> 
  
  
<img src="https://wallpapercave.com/wp/wp4078364.jpg">
  
### <center>Overview</center>
* **Basic Idea :**<br>
Climate change is one of the most concerning problem in the world.The basic mechanics of climate change are simple: Carbon dioxide in the atmosphere traps heat. More carbon dioxide means more heat is trapped across the Earth, causing it to warm up. And the temperature is gradually increasing.Machine learning can be used to predict this time dependant variable. Also the temeprature is affected by other environmental factors like Humidity,Wind speed, Density of air and others. So over machine learning, Deep learning can be handfull for better predictions.
   **The time series climate change forcasting model can be used to forecast Temprature for future for specific time period**

* **Objective :**<br>Neural Networks in deep learning can be used to detect the pattern in the historical data and can be useful to create a prediction.Utilizing the Data analysing and Machine Learning to forecast climate change.<br>


* **Problem Statement :**<br>TIme series analysis of climate change .


* **Motivation :**<br>Weather forcasting is basic every day foreasting we see on television or any brodcasting media.a curiosity about how prediction is done, can be usefull to learn.Applying machine learning to analysis data and learn the pattern is intresting to learn. 


* **Project Scope :**<br>This  project will analyise the historical data of climate data of Jena (Germany) city, take insight from that data to understand more about how climate is changing over the years by the view of temprature. At the last stage of project will be creating a deep learning model that understand this problem to give us desired output.


* **Working Methodology :**
    - Primary Task is to Understand Data and finding anomalies in data.
    - Feature Engineering.
    - Exploratory data analysis.
    - Model Preprocessing.
    - Neural Network model building.
    - Model Evaluation.
    - Forecasting.
    
* **Data Collection**
    - link for the dataset is <a href='https://storage.googleapis.com/tensorflow/tf-keras-datasets/jena_climate_2009_2016.csv.zip'>HERE</a>


* **Technical Aspect :**<br>
    - [Python v1.2.4](https://www.python.org/) Programming Langauge for this Notebook.
    - [Pandas v1.21.2](https://pandas.pydata.org/) Python Data Analysis Library.
    - [Sklearn v0.24.2](https://scikit-learn.org/stable/) Machine Learning handling in Python. 
    - [Matplotlib v3.4.2](https://matplotlib.org/) creating static, animated, and interactive visualizations in Python.
    - [Seaborn v0.11.1](https://seaborn.pydata.org/) Python data Visulization based on matplotlib.
    - [Statsmodels 0.12.2](https://www.statsmodels.org/stable/index.html)  Statsmodels is another machine learning library for python.
    - [Tensorflow 2.7.0](https://www.tensorflow.org/) Tensorflow is a Deep learning library that handles many of the deep learning problems.
  
  
  
##  **Result**
  
  
|Model|Train RMSE	|Val RMSE	|Test RMSE|
|-----|-----------|---------|---------|
|LSTM|0.262661|0.261583	|0.237998|
|CNN	|0.331631	|0.340288|	0.351175|
|	GRU	|0.268511	|0.262868|	0.245132|
