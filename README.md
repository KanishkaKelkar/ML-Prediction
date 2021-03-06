# Diamond Price Prediction

# Objective:-
To build a web application where users can look up a predicted price for their desired diamonds.

# About Data:-
For this project, I used a dataset from Kaggle performed EDA & data preprocessing, built a regression model to predict the price of the diamond using basic diamond measurement metrics. Each diamond in this dataset is given a price. The price of the diamond is determined by 7 input variables:

# Feature description:-
1)price:- price in US dollars ( 326−− 18,823)This is the target column containing tags for the features.

2)carat (0.2--5.01) The carat is the diamond’s physical weight measured in metric carats. One carat equals 1/5 gram and is subdivided into 100 points. Carat weight is the most objective grade of the 4Cs.

3)cut (Fair, Good, Very Good, Premium, Ideal) In determining the quality of the cut, the diamond grader evaluates the cutter’s skill in the fashioning of the diamond. The more precise the diamond is cut, the more captivating the diamond is to the eye.

4)color :- from J (worst) to D (best) The colour of gem-quality diamonds occurs in many hues. In the range from colourless to light yellow or light brown. Colourless diamonds are the rarest. Other natural colours (blue, red, pink for example) are known as "fancy,” and their colour grading is different than from white colorless diamonds.

5)clarity :-(I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)) Diamonds can have internal characteristics known as inclusions or external characteristics known as blemishes. Diamonds without inclusions or blemishes are rare; however, most characteristics can only be seen with magnification.

6)X, Y, Z are the dimensions of the Diamond :-
x length in mm (0--10.74)
y width in mm (0--58.9)
z depth in mm (0--31.8)

7)Depth :- The depth of the diamond is its height (in millimetres) measured from the culet (bottom tip) to the table (flat, top surface).

8)Table :- A diamond's table refers to the flat facet of the diamond seen when the stone is face up. The main purpose of a diamond table is to refract entering light rays and allow reflected light rays from within the diamond to meet the observer’s eye.

# Procedure:-
1) Import library
2) Load dataset
3) EDA & Preprocessing : drop least important feature, descriptive statistics, pairplot, visualisation, drop outliers, corelation, Encoding
4) Model Creation : divide into x & y, train test spilt, models are Linear Regression, Random forest Regressor, DecisionTreeRegressor, XGBRegressor, GradientBoostingRegressor
5) Hyperparameter Tunning 
6) Cross Validation
7) Deploy model using flask


# Website link :-
https://diamond-price-predict.herokuapp.com/
