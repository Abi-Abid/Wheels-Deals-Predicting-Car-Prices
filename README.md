![dan-gold-N7RiDzfF2iw-unsplash](https://github.com/user-attachments/assets/4dd39ae5-5cc5-4b58-ad55-ecba08ea0e60)

# Used Car Price Prediction Using ML
**"Hey, Looking for the right price on a specific car model? No worries—let me ask my ML agent and get you an accurate estimate in seconds!”**

## Introduction 

In this project, we aim to build an accurate Machine Learning (ML) model that predicts the prices of used cars based on their specifications. While this may initially sound simple, the real-world applications are highly valuable. Imagine you're part of a car dealership, and a customer walks in asking for the price of a specific car model with certain features. With dozens of models and varying configurations, determining an accurate price on the spot can be challenging.

Now, picture having a smart system or ML model on your tablet—where you simply enter the car’s details, and within seconds, it provides a reliable price estimate. Sounds exciting, right? That’s exactly what this project sets out to achieve.

# Key Insights

Based on the findings and comprehensive analysis:

- It was observed that the original dataset comprised 205 rows and 26 columns, representing 205 cars with 26 different specifications. Upon analyzing the price distribution, it was noted that the data was right-skewed, indicating a higher number of low-priced cars compared to expensive ones.
- Additionally, scatter plots of both numerical and categorical features showed a significant presence of outliers, which could negatively impact model performance. To address this, outliers were treated using the Interquartile Range (IQR) method, which resulted in a reduced dataset of 185 rows.
- Despite the reduction, this cleaned dataset contained more consistent and evenly distributed price values, contributing to improved model stability.

After preprocessing, including one-hot encoding of categorical variables and standardization of numerical features, the dataset was split into training and testing sets with a **70-30 ratio.** Several machine learning models were trained and evaluated for performance. 

- Among these, **Ridge Regression and AdaBoost Regressor demonstrated the best results,** achieving approximately **87% accuracy (R² score)** and comparatively lower MAE and RMSE values.
- On the other hand, Polynomial Regression (Degree 3) and Support Vector Regressor (SVR) performed poorly, with high errors and low predictive accuracy.

Due to the relatively small size of the dataset, no hyperparameter tuning was applied during model training. This decision was made to avoid the risk of overfitting or underfitting, ensuring that models learned the underlying data patterns without overcomplicating them. Ultimately, Ridge Regression emerged as the most reliable model, offering strong performance and serving as a solid foundation for future expansion as more data becomes available.

In practical application, especially in a used car dealership context, **the Ridge Regression model can be effectively used to predict the selling price of a car based on its specifications.** This not only aids buyers in making informed decisions but also helps sellers in setting fair and accurate prices. Below picture gives the results of all ML models analyzed. 


<img width="641" alt="imageqsqw" src="https://github.com/user-attachments/assets/52027d95-ac9a-48bb-9341-cdbaec1a2c84" />

---
## Author
**Dudekula Abid Hussain**

Email iD - dabidhussain2502@gmail.com

Thanks for stopping by! If you found this helpful or have suggestions, feel free to leave feedback. Happy learning and exploring new data! 👏
