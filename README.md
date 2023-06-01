# **Medical Insurance Premium Project**

![image](https://github.com/JoeBwonKenobi/Medical_Insurance_Premium_Project/assets/117705408/b376a9cc-3ca7-462b-a1ff-0c95307d4207)

Building a machine leraning model to predict yearly medical insurance premiums.

# **Overview:**

Health and medical insurance provide financial assistance to policyholders in case of medical emergencies by covering their expenses. An accurate determination of the insurance premium, based on factors such as age, health history, and profession, is crucial for building strong customer relationships, customizing health insurance plans, reducing risks, and making better decisions in risk management. This project uses data from an insurance company and creates a model to predict the premiums to help make an informed descision.

# **Data Source:**
https://www.kaggle.com/datasets/tejashvi14/medical-insurance-premium-prediction?resource=download

# **Methods**

# **Exploratory Visualizations**

# **Distribution of Premium Prices**

![image](https://user-images.githubusercontent.com/117705408/235576300-7d34449e-9f8e-4347-a405-3e3c01894d14.png)

- The thing we want to firure out is called "PremiumPrice", and it  doesn't look like a bell curve when we plot it out. 
- This means we might need to use some special methods when we try to create models that explain PremiumPrice.

# **Premium Price for Age**

![image](https://user-images.githubusercontent.com/117705408/235576347-9e1fd6f4-87b0-473d-b9ca-5ccfd3207d48.png)

# **Premium Price for Height**

![image](https://user-images.githubusercontent.com/117705408/235576479-3fb41200-47af-42e1-8e76-8669cc37e1e3.png)

# **Premium Price for Weight**

![image](https://user-images.githubusercontent.com/117705408/235576532-55bf1548-583f-42b4-80d8-8041f6c0bc21.png)

- When we look at the graph that shows the heights and weights of different people, we don't see any clear pattern that suggests people who are taller also weigh more or people who are shorter also weigh less. 
- We also looked at whether height and weight have a strong connection with Premium Price, but there doesn't seem to be a noticeable relationship there either.
- So we might need to either leave out height and weight from our analysis or combine them into a new measurement called BMI that has a more obvious impact on Premium Price.

# **Predictive Models**


## **Random Forest Regressor**


![image](https://user-images.githubusercontent.com/117705408/235576792-feaf08f6-b65f-468a-bbf3-22d4ff3a46bb.png)

# **XGBRF Regressor**

![image](https://user-images.githubusercontent.com/117705408/235576889-0603fa85-eca7-4111-92da-ea7a19560e48.png)

# **Model Performance**

# **Recommendations**

# **Limitations & Next steps**
