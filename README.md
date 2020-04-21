## COVID19 India Predictions
This project intends to predict the number of cases and deaths due to COVID19 in India.

## Requirements
 The following packages are needed to be installed for this project to run:
    - numpy
    - matplotlib
    - scikit-learn
    - pandas
    - os
    - csv
    - json
    - requests
    - datetime
## Usage

1. Install dependencies
2. Run `python3 main.py`

## Working

The main.py file uses the IndiaCovidCases/Deaths class to scrap the data from https://api.covid19india.org/data.json.
The main.py file then trains the configured model.
Then, the file displays the models' predictions for cases and deaths due to COVID19 in India for desired number of days.


## Own Dataset

If you have that same json format of you data then you can simply replace it with the link.
Else
Create a new  class and replace it by IndiaCovidCases and implement the two methods in the class in the same format i.e  this method should fetch the data from a data source and store it into a file.

## output

![picture](Figure_1.png)
