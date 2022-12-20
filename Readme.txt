Predicting for Car type using machine learning techniques


Data Source:
https//www.kaggle.com/datasets/conorsully1/pdp-and-ice-plots

Data also included in repository.


Project file: Car Sales no Smote, RFE, Logistic Regression.ipynb

The purpose of this project was to gain an introductory level of knowledge to logistic regression for classifying.


Input Variables
1 - owner_age: Age of the previous owner in years (numeric)

2 - car_age: Age of car at time of sale in years (numeric)

3 - km_driven: Distance driven at time of sale in kilometers (numeric)

4 - repairs: The number of times the car has been serviced/repaired (numeric)

5 - price: The $ price the second hand car was sold for (numeric)

Predict Variable
y - car_type: A normal (0) car or a classic (1) car


The objective for the classification was to design an accurate model that could be used to predict for the dummy variable car_type.

I used python, pandas, numpy, matplotlib, seaborn, scikit-learn, and statsmodel to perform dataframe cleaning, data visualization, data analysis,
and machine learning model building.

The techniques that I utilize at first are correlation heatmapping to highlight potential important relationships.

Through my econometrics background, I recognized a potential model complication due to a correlation between two input variables. 

I then analyzed to gain insight with regards to the relationships between the each of the input variables split by car_type utilizing box
plots. After investigating, I decided the best option would be to use RFE: Recursive Feature Elimination in order to reinforce my feature
selection choices. Finally, I built a logistic regression model that achieved a high amount of accuracy while maintaining the ability to
predict for the minority car_type group.


Auxillary files
---------------------------------------------------------------------------------------------------------------------------------------------------------------
archive.zip: PDP_ICE.csv
PDP_ICE.csv: The actual data from the data source, however it is tab deliniated instead of comma deliniated
PDP_ICE_fixed.csv : The data from the data source in proper comma deliniated format
TSV to CSV: file used to convert to proper comma deliniated format (manually edited the first row, deleted quotation marks surrounding each of the 6 strings)
---------------------------------------------------------------------------------------------------------------------------------------------------------------
