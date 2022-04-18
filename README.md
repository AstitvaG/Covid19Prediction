# Predicting India’s COVID-19 Third Wave with LSTM

## Team `ATTACK`

## Disaster Management CE8.401

### MEMBERS

```text
Astitva Gupta, 2018101085
Karsh Tandon, 2018101034
Kartik Agarwal, 2018102017
Tanmay Pathak, 2018102023
```

### _Project of predicting new COVID-19 cases in the next `90 days` with LSTM_

## Dataset

The dataset is downloaded from ‘[COVID-19 India Datasets by DataMeet](https://projects.datameet.org/covid19/)’. The data is community collected, cleaned and organized from different government websites which are freely available to all the Indians.

Github Repository: [https://github.com/datameet/covid19](https://github.com/datameet/covid19)

The dataset has a Creative Commons Attribution 4.0 International Public License.

**The dataset for before 3rd wave contains data upto `10 January 2022`.**

**The dataset for predicting future wave is downloaded on `19 April 2022` and contains data up to the same date.**

We are using the file all_totals.JSON in the data directory.

## Technology

We have used the artificial recurrent neural network (RNN) architecture Long Short-Term Memory (LSTM) for this project. The CovidPredictionLSTM.ipynb file is the Jupyter Notebook file containing all of the work.

This project showcases the usage of the LSTM architecture in predicting time-series data. In this case, we used the COVID-19 data from India for our study.

This model does not consider transmissibility and other factors while making the predictions.
