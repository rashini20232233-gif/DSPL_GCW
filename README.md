# Machine learning models for hotel revenue prediction

**Overview**

Hotel chain A, a leading hospitality group, is associated with operating hotels across multiple geographical regions such as cities, airports and resorts. They are engaged in providing accommodation, dining and other facilities all along while managing the reservations among multiple booking channels. 

**Project Context**

Although Hotel Chain A faces high volume with their service providing facilities, they have been facing a significant revenue loss due to the high no show and cancellations. The company aims to have an analytical solution that much improves their revenue patterns, creating a positive impact..
The main problem we are focused on is the Cancellation of Bookings and No shows and how it affects the revenue. This is the problem domain which later onwards has to be fixed considering the correlation with the revenue of Hotel Chain A. 

**Objectives**

•	Develop an analytical model to predict booking outcomes (Check-in, Cancelled, No-show) 

•	Identify key factors influencing cancellations and no-shows 

•	Address challenges related to class imbalance in the dataset 

•	Improve decision-making for revenue optimization 

•	Provide actionable insights to enhance operational efficiency 


**Data**

The project utilizes hotel booking datasets containing customer, booking, and stay-related information such as:

•	Customer demographics (Age, Gender, Income, Region) 

•	Booking details (Lead time, Booking channel, Deposit type) 

•	Stay details (Room rate, number of guests, nights) 

•	Promotions and discounts 

•	Reservation status (target variable) 


**Datasets**

• train.csv: Used for model training

• validation.csv: Used for model validation

•	test.csv: Used for final predictions


**Methodology**

**Data Preprocessing**

•	Handled missing values and inconsistencies 

•	Converted categorical variables using encoding techniques 

•	Created new features such as: 

o	Lead time 

o	Stay nights 

o	Total guests 

•	Removed irrelevant or redundant features 

**Exploratory Data Analysis (EDA)**

•	Univariate and bivariate analysis to understand patterns 

•	Visualization techniques: 

o	Histograms 

o	Box plots 

o	Scatter plots 

o	Correlation heatmaps 

•	Identified relationships between features and booking outcomes 

**Feature Selection**

•	Applied Spearman correlation to identify important features

•	Selected top features influencing booking outcomes 

**Model Selection**

The following machine learning models were considered:

•	Decision Tree 

•	Artificial Neural Network (ANN) 

•	LightGBM 

•	Random Forest

**Model Evaluation**

The models were evaluated using:

•	Accuracy 

•	Precision 

•	Recall 

•	F1-Macro (primary metric for imbalanced data) 

•	Confusion Matrix 

**Contributors**

•	Saarah – Project Manager 

•	Poornima – Data Engineer 

•	Rashini – Data Analyst

•	Disandi – Business / Revenue Analyst 

•	Vishud – ML Specialist 

•	Bilal – Model Tester / QA 


**Acknowledgements**

We would like to express our sincere gratitude to our lecturers and project supervisors, Mr. Fouzul Hassan and Mr. Himasha Randil for their continuous guidance and support throughout this project. Their feedback and insights greatly contributed to the successful completion of this work.

