# UABeat

Welcome to the repository of UABeat, the project oriented to help the university optimize energy consumption for the Faculty of Engineering at the Autonomous University of Barcelona (UAB). This tool aims to provide actionable insights and predictions to the energy department, enabling them to make informed decisions to save energy. 

The repository is structured with a folder containing all the datasets that have been used and then all the code that has been implemented.

For starters, there is the _Consum_energia_ model, that uses the _Consum_energia.xls_ dataset, this includes the energy consumption of the engineering faculty by the hour. The code preprocesses the dataset, optimizing it for the task the model is oriented; it gives several graphs visualizing the data, such as the consumption per month over the years; creates the _monthly_price.csv_ dataset, that is a dataset of how much the university has spent on electricity each month, such dataset was key to determine the approximate savings that could be done; finally in the code is created and implemented the model for future predictions of energy consumption, including graphs on the performance over the ground truth and one month after the data is exhausted.

Moving on there is the _Consum_mensual_ code, that employs the _consum_mensual.xls_ dataset, which contains the monthly gas consumption of the engineering faculty. The code preprocesses the dataset; offers some visualization on the data, sucha s the consumption per month and year; and there is a model developed and tested that forecasts the gas consumption, including a visualisation of the loss difference between the training and validation data of the model, providing insgihts on the efficiency of the model.

Furthermore, there is the _sensors_forecasting_ code, based on the _Sensors_cleansed.csv_ dataset, which is inside the _Sensors_cleaned.zip_ zip file, such dataset provides data on the values of humidity, CO2 and interior temperature colelcted by the sensors distributed around the engineering faculty. The code's purpose is to do some forecasting on the hunmidity, CO2 and temperature; there is some visualization of the predictions contrasted with the ground truth to see the performance over the known data and also predictions after the last data entry.

Moreover, there is the _Production_Synthesis_ code, using the _production.csv_ it aims to preprocess the data, provide some visualizations on it and create a model that predicts future production, such model, however, is failed and it should not be taken into account.

In addition, there is the _ocupacio_ code, that uses the _ocupacio_enginyeria_2022.xlsx_, the dataset provides information about the amount of people that is supposed to be at each class at each time of the day. Due to the fact that this dataset was not used to create any model, that was only kept in case it could be used in the future work, the code only cleans the data and provides some visualizations of it.

