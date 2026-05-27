# Solar-Energy-Management-System-with-Machine-Learning-Based-Load-Scheduling

SYSTEM IMPLEMENTATION
System Design and Description
ESP32
Solar Panels (6V 100mA &12V 100mA)
AHT20 Temperature and Humidity Sensor
LoRa Transmitter and Receiver (RA02 AI Thinker)
Li-ion 2000mAh 3.7V Battery
DC Motor

Flow chart/ Algorithm implemented-
Data Analysis and Prediction Algorithm:
Combine transmitted over time to create historical dataset
Train a model using Random Forest machine learning algorithm with this data set where;
Random Forest model is defined by specifying number of decision trees (estimators) and other hyperparameters that affect its accuracy during training process.
Input features such as time of day, temperature, humidity are fed into the model together with target output which is solar power output Training patterns in the data that can be used to predict future outcomes are searched by training models on them so periodically retraining models based on new inputs helps keeping up-to-date besides improving prediction performance also re-uses same algorithms without need for additional computations at each prediction step because it’s faster than other methods like linear regression but slower than gradient boosting method.
Use trained model to forecast solar energy production in future based on upcoming weather forecasts obtained through OpenWeather API which gives future temperature, humidity cloud cover information among others.

Load Scheduling Algorithm-
Steps:
Receive Random Forest’s predicted power output.
Find total power requirement of all appliances connected (e.g high voltage LEDs Heavy DC motor).
If predicted power output meets or exceeds total load then continue operating them normally otherwise reduce loads one by one starting with highest priority until sum is within safe limit of predicted power:
Temporarily switch off non-essential loads or lower priority ones.
Reconfigure these loads’ operational parameters so as to balance total current consumption against available supply continuously within an hour or any other specific period depending on new predictions and actual generation levels update.

RESULTS AND ANALYSIS
Results of Implementations
The “AI-Based System for Solar Panel Load Scheduling and Predictive Analysis” has given very good results that prove that IoT and artificial intelligence technologies can be used to manage and optimize solar energy systems. This part of the report explains what each component achieved.

