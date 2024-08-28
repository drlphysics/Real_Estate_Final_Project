# HomePriceAI
#### HomePriceAI is a machine learning project that leverages real estate data from the Multiple Listing Service (MLS) to predict home sale prices. By utilizing advanced techniques such as Gradient Boosting Machines (GBM) and Natural Language Processing (NLP), this project aims to improve the accuracy and performance of price estimation models. Our goal is to provide a robust and scalable solution for the real estate industry to make more informed decisions based on data-driven insights.

# Table of Contents 

## 1. [Methodology](#methodology)
- [Data Collection](#data-collection)
- [Data Exploration](#data-exploration)
- [Data Engineering](#data-Engineering)
- [Model Selection](#model-selection)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
## 2. [Tools](#tools)
## 3. [Team Members](#team-members)
## 4. [Installation](#installation)
- [Steps to install](#steps-to-install)
## 5. [Usage](#usage)

## 6. [Contribution](#contribution)

## Methodology <a name="methodology"></a>

### Data Collection <a name="data-collection"></a>
 - Sources: MLS Data for the Triangle Area
 
 - Data Features: MLS #, Class, Property Type, Address, City, Zip, Neighborhood, Subdivision, Bedrooms, Total Baths, Total Living Area SqFt, Acres, Year Built, List Date, Closing Date, Days On Market, List Price, Sold Price.




### Data Exploration <a name="data-exploration"></a> 

  - Statistical Analysis: '.describe()', '.info()', '.value_counts()', 'z-score', 'df.corr()' 


### Data Engineering <a name="data-Engineering"></a> 
 - Data Cleaning: Handling null entries, correcting errors, dropping missing values, converting value types to integers.


 - Transformation: 'StandardScaler()', 'OneHotEncoder()'
 - Created a deep learning neural network, from which spatial features could be extracted from the dense layers, and plugged back into the regression models using a hybrid approach.



### Model Selection <a name="model-selection"></a> 
 - Random Forest
 - NLP
 - XGBoost
 - CatBoost
 - LightGBM

### Model Training <a name="model-training"></a> 
 - Data Splits: 'train_test_split()'
 - Hyperparameters
 - Hyperparameter Tuning: BayesSearchCV, GridSearchCV


### Model Evaluation <a name="model-evaluation"></a> 
- Scoring Methods:
    - MSE
    - Mae
    - r2
    - rsme
    - neg_mean_squared_error



### Tools <a name="tools"></a>
- Gradient Boosting Machines (GBM): Utilizes GBM to build an accurate and scalable model for predicting home prices.
- Random Forest: Implements Random Forest to improve prediction accuracy and robustness through ensemble learning.
- Natural Language Processing (NLP): Incorporates NLP techniques to analyze and leverage textual data.
- Bayesian Optimization: Employs BayesSearchCV for hyperparameter tuning to optimize model performance.
- GridSearchCV: Employs GridSearchCV for hyperparameter tuning to optimize model performance.

### Team Members <a name="team-members"></a>
- Catina Wright 
    - Github: https://github.com/CatAIGeek
    - Linkedin: https://www.linkedin.com/in/catinawright1/
- Amelia Fernandez
    - Github: https://github.com/aFernandez88
    - Linkedin: https://www.linkedin.com/in/amelia-fernandez-17a56220b/
- David Little
    - Github: https://github.com/drlphysics
    - Linkedin: https://www.linkedin.com/in/david-little-phd-67b360185/
- Brandi Berry
    - Github: https://github.com/brandialyssa95
    - Linkedin: https://www.linkedin.com/in/brandi-berry-ba2b871a5/
- Kurt Andreassen
    - Github: https://github.com/kurtandreassen
    - Linkedin: https://www.linkedin.com/in/kurt-andreassen-aa13352/

### Installation <a name="installation"></a>
- ### Steps to install <a name="steps-to-install"></a>
    1. Download the latest version of Python
    2. Use the 'git clone' command to clone repository: https://github.com/drlphysics/Real_Estate_Final_Project
    3. 'cd' Real_Estate_Final_Project
    4. Install Dependencies: Ensure you have the necessary packages installed. You can use pip to install the required dependencies.
    5. Prepare the Data: Place your MLS data in the data/ directory. Ensure that the dataset is correctly formatted for the model.
    6. Run the Model: Execute the script to train and evaluate the model.


## Usage <a name="usage"></a>
  1. Explore the data
  2. Preprocess the data
  3. Train the model
  4. Evaluate the model
  5. Deploy the model


## Contribution <a name="contribution"></a>
Your contributions are highly valued! Feel free to submit a pull request or open an issue to share your ideas.
