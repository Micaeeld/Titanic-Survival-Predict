##### Use https://nbviewer.org to upload the file in case of errors
---

# Titanic Survival Prediction
This notebook presents a prediction of survival on the Titanic, using a data set available in Kaggle. The dataset contains information about passengers aboard the Titanic, including age, gender, class, and more. The specific dataset used in this project can be found at https://www.kaggle.com/competitions/titanic/data.

## Data set
The dataset consists of 891 rows and 12 columns. Columns include:

- Passenger ID: unique passenger identifier
- Survived: indicates whether the passenger survived or not (0 = did not survive, 1 = survived)
- Class: passenger class (1 = first class, 2 = second class, 3 = third class)
- Name: name of the passenger
- Gender: Passenger's gender (male or female)
- Age: age of the passenger
- Number of siblings/spouses on board
- Number of parents/children on board
- Ticket: passenger ticket number
- Fare: value of the passenger fare
- Cabin: passenger cabin number
- Port of embarkation: port of embarkation of the passenger (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data preparation
Before creating the survival prediction model, the data was pre-processed and prepared for training. Some of the data preparation steps include:

- Cleaning of missing data and outliers
- Coding of categorical features
- Data normalization
- Survival prediction model
To predict survival on the Titanic, the GradientBoostingClassifier model was used. The model was trained using passenger characteristics as the independent variable and survival as the dependent variable.

The results showed that the model presented an accuracy of 84%.

## Conclusion
This notebook presented a prediction of survival on the Titanic using a data set available in Kaggle. The Decision Tree model was able to accurately predict whether or not a passenger survived based on their personal characteristics. Survival forecasting can be useful for insurance companies that want to assess the risk of sea voyages.


## Contribution

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.
