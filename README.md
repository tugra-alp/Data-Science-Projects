# Overwiev of Projects

Hi, I am Tugra. I am a engineer who is curious about Machine learning and artificial intelligence and stepped into this field with a master program in Istanbul :blush:. My goal is to learn something new every day and make more projects :muscle: so here is the small portfolio for you. You can check description of whole my projects that i pushed.
 
## [Project 1: Bengaluru House Project : Predict House Prices](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project1-Bengaluru%20House%20Project)

In this project, I actually try a low-code python module which name is LazyPredict to see how it works. LazyPredict is allow us to see **which model can fit better**, with a few line codes and without any parameter tuning. Thus you get some insight which model or models can fit your data before using these models with hyperparameter tuning.
Here is the link of the [LazyPredict Documentation](https://lazypredict.readthedocs.io/en/latest/index.html)

Project steps:

- Get the result of regression algorithms in LazyPredict, here is the top 3 models fitted the data:
  1. MLPregressor in Lazypredict =  **Adj. R2:** 0.87 **RMSE:** 23.38 
  2. BayesianRidge in Lazypredict = **Adj. R2:** 0.84 **RMSE:** 26.65
  3. Linear Regression in Lazypredict = **Adj. R2:** 0.84 **RMSE:** 26.67
- Then I used **MLP(Multi-Layer Perceptron)** algorithms with Sklearn module to train data.
- GridSearchCV was used for hyperparameter tuning.
- Finally, I got the result of the test set.
   **RMSE :** 22.45
   **R2 of Tuned Model:** 0.902

## [Project 2: (End-to-End) Celebrity Face Recognition : Image Classification with SVM](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project2-Celebrity%20Face%20Recognition)
In this machine learning project, I classify celebrity personalities. I restrict classification to only 5 people. This project includes from data collection **(Image Scrapping)** to Deployment on AWS. Random Forest, Logistic Regression and Support Vector Machines algorithm were used for this study, and GridSearchCV method was used for model selection with tuning parameters.

**Choosen People:**
1. Cristiano Ronaldo
2. Cheki Chen
3. Brad Pitt
4. Johnny Depp
5. Lionel Messi

![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project2-Celebrity%20Face%20Recognition/Project%20Outcome%20Screenshots/Celebrity%20Person%20Classifier%20Ex1.png)

**Here is the folder structure:**
* **UI:** This contains ui website code 
* **server:** Python flask server 
* **model:** Contains python notebook for model building 
* **google_image_scrapping:** Code to scrap google for images 
* **datasets:** Dataset used for our model training which includes celebrity images 

**Technologies used in this project:**
1. Python :arrow_lower_left:
2. Numpy and OpenCV for data cleaning :arrow_lower_left:
3. Matplotlib & Seaborn for data visualization :arrow_lower_left:
4. Sklearn for model building :arrow_lower_left:
5. Jupyter notebook, visual studio code as IDE :arrow_lower_left:
6. Python flask for http server :arrow_lower_left:
7. HTML/CSS/Javascript for UI :arrow_lower_left:

**A Screenshot after model deployment**

![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project2-Celebrity%20Face%20Recognition/Project%20Outcome%20Screenshots/Model%20Deployment%20on%20AWS.jpg)

## [Project 3: Data Analysis Project On TABLEAU : Sales Insight](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project3-TABLEAU%20Data%20Analysis%20Project)

The case study is based on a computer hardware business which is facing challenges in dynamically changing market. Sales director decides to invest in data analysis project and he would like to build Tableau dashboard that can give him real time sales insights. 

**Simply,insights could be:**
 - Revenue breakdown cities
 - Revenue breakdown by years and months
 - Top 5 customers by revenue and sales quantity
 - Top 5 products by revenue number
  etc. 

**Project Steps:**

1. import the "db_dumb.sql" file to MySQL DB and getting some knowledge about data.
2. Plug MySQL with Tableau.
3. In Tableau, do data cleaning, ETL(Extract, transform ,load), currency normalization and handling invalid values etc.
4. And.. Make Dashboard !!

**Note:** "db_dumb.sql" used for Revenue Analysis - "db_dumb_version_2.sql" file used for Profit Analysis 
- Revenue Dashboard

![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project3-TABLEAU%20Data%20Analysis%20Project/Dashboard%20-%20Revenue%20Analysis.png)

- Profit Dashboard

![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project3-TABLEAU%20Data%20Analysis%20Project/Dashboard-Profit%20Analysis.png)


## [Project 4: Breast Cancer : ML Classification Project](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project4-Breast%20Cancer)

Predicting if the cancer diagnosis is **benign** or **malignant** based on several observations/features. Support Vector Classification algorithm used for this study with GridSearchCV method to reach best model parameter.

**30 features are used, examples:**

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry 
  - fractal dimension ("coastline approximation" - 1)
Datasets are linearly separable using all 30 input features

Number of Instances: 569

Class Distribution: 212 Malignant, 357 Benign

Target class:

   - Malignant
   - Benign

Dataset: **https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)**


## [Project 5: Fashion MNIST Dataset : Image Classification with CNN](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project5-Fashion%20Mnist)

Basic Deep Learning project to predict class of attirbutes with Convolution Neural Network using Fashion mnist dataset.

- Dataset : https://www.kaggle.com/zalando-research/fashionmnist


## [Project 6: (End-to-End) Predicting of Zomato Restaurant Ratings  : Regression Task / Flask Deployment](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project6-%20Zomato%20Restaurant%20Ratings)

![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project6-%20Zomato%20Restaurant%20Ratings/output-images/input-given.png)


**The main agenda of this project is:**
- Perform extensive Exploratory Data Analysis(EDA) on the Zomato Dataset
- Build an appropriate Machine Learning Model that will help various Zomato Restaurants to predict their respective Ratings based on certain features
- DEPLOY the Machine learning model via Flask that can be used to make live predictions of restaurants ratings


![](https://github.com/tugra-alp/Data-Science-Projects/blob/main/Project6-%20Zomato%20Restaurant%20Ratings/output-images/predicted%20result.png)

## [Project 7: Flight Price Prediction with XGBoost: Regression Task](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project7-%20Flight%20Price%20Prediction)

- It is a Regression task to predict flight price with given inputs.
- Performed EDA and some feature engineering technics such as one-hot encoding.
- Sklearn and Pycaret modules were used in modelling part.
- Applied LightGBM - CatBoos and **XGBoost** algorithms with GridSearchCV method.
- **Source :** [Kaggle](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh)


## [Project 8: Credit Card Fraud Detection : Deep Learning Task](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project8%20-Credit%20Card%20Fruad%20Detection)


- Dataset is from [kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Applied some visualizations to perform EDA
- Handling with imbalanced data to using **Downsampling** and **SMOTE**
- Modelling with **Desicin trees**(Sklearn) and **Convolutional Neural Network**(Keras)


## [Project 9: Stock Market Analysis with Using K-means : Unsupervised Task](https://github.com/tugra-alp/Data-Science-Projects/tree/main/Project9-%20Stock%20Market%20Clustering)

- Fetching 27 companies data from **Yahoo Finance** with using pandas-datareader module
- Used pipeline to applying **normalize , PCA and K-means**
- There will be further studies on Stock Prices such as more effective visualizations and applying **Deep Learning methods like LSTM**


