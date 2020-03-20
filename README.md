# Corona-Virus-Outbreak-Prediction
This is an open chllange by machinehack.com. This project aims to predict the outbreak of corona virus all over the world. Here the number of infected people, the number of deaths and the number of recovered people is predicted for the next day for all the 155 countries based on the records of these upto the previous day for respective countries.
# Dataset
The dataset is given by machinehack.com and it is updated daily. The datasets are 3 csv files denoting confirmed people, recovered people, death of the people for everyday since 22nd january 2020 upto this day. 
# Training
Based on the daily updated data the training is done and the results are collected. For training RNN model is used to make prediction of the time series data. To make the network one LSTM network and one fully connected network(DENSE) is used. The model is trained everyday.
# Result
The result is predicted for death, recovered and confirmed issues everyday using the trained model then they are combined and the result is generated.
