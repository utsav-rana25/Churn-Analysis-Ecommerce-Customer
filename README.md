## Full Stack Data - Churn Analysis Ecommerce Customer

**Problem Statement :**
The E-commerce customer churn rate is up to 80% compared with traditional business customer management. From dataset customer churn is 17%.

**Goals :**
The purpose of this project is to predict customer churn, loss opportunity and provide recommendations to the business team so the company can implement a persona customer retention strategy and can monitoring throught dashboard interactive.

**Tools**: Python, JupyterLab, Git, PowerBI

**Libraries**: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn, kaplan-meier survival curve, lifelines.CoPHfilter, lifelines.predict_survival_function, K-means, gaussian, rfm-segmentation

**Summary of the analysis**
* This dataset has 5630 observations and 20 variables with 15 numerical variables, 5 categorical variables and 2 target variable.
* From the data visualization, it is obtained that the churn ratio has a correlation with tenure, complaints, cashback Amount, & preferred order cat.
* The results of predicting churn are strongly influenced by the level of Tenure, Complaint, Number of Addresses, and cashback Amount.
* The results of the Survival Analysis, the customer has the greatest survival chance in No Complain, Marital Status Married, Payment Mode Credit Card, Order Category Grocery.
![image](https://user-images.githubusercontent.com/108534539/206370747-d154f74b-505d-4725-9974-2c3b094e8986.png)
* RFM Segmentation results show priority customer treatment in the Loyal, New, Promising, and Lost Potential segments. 
![image](https://user-images.githubusercontent.com/108534539/206370814-ec56637b-f46d-4522-9f38-5a6dca882b46.png)
* Total Expected Loss of $ 910,687
* Estimated Revenue Uplift
  *  Order category Grocery $42,448
  *  Payment Credit Card $ 91,785 
  *  Payment Debit Card $ 78,543

![image](https://user-images.githubusercontent.com/108534539/206370164-cb8e97d4-f39f-48d1-9a86-2d8e265f25a5.png)

![image](https://user-images.githubusercontent.com/108534539/206371381-5df36ef3-8bfc-40ed-8ac5-7ed4383b450e.png)


**What I have learned**
* Framing the business problem. 
* Create a machine learning model and extract insight that generates churn & retention from it to make an actionable recommendation for the business team.
* Create a survival analysis, predict customer who will churn in Future and extract insight that generates churn & retention from it to make an actionable recommendation for the business team.
* Create a customer segmentation with RFM Segmentation, KMeans and Gaussians that can generates strategy-strategy personal customer. 
* Create a dashboard interactive can monitoring business metrics, operational, and sales.
* Make a business simulation from insights that calculate loss oppurtunity and revenue uplift.


