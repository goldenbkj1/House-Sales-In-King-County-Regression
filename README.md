# House-Sales-In-King-County-Regression
This project is dedicated to analyzing the "kc_house_data" dataset and developing machine learning models for predicting house prices in King County, Washington. We aim to provide valuable insights into the factors influencing house prices in this region.

<img src= "https://media.tenor.com/Dyg_gZa4Vl4AAAAC/for-sale.gif">

## Tools and Technologies

We leverage the following tools and technologies for this project:

- **Python**: The primary programming language for implementing machine learning algorithms and conducting data analysis.
- **Jupyter Notebooks**: Used for creating and sharing interactive code documents that facilitate data exploration, model development, and evaluation.
- **Scikit-Learn**: Provides a comprehensive suite of machine learning algorithms and tools for model development and assessment.
- **Pandas and NumPy**: Employed for data manipulation, preprocessing, and feature engineering.
- **Matplotlib and Seaborn**: Used for data visualization, enabling the creation of insightful visual representations.

## Analysis Objectives

Our analysis focuses on several key objectives:

1. **Data Exploration**: Gaining a comprehensive understanding of the dataset, including identifying missing values, outliers, and initial insights into feature relationships.

2. **Data Preprocessing**: Cleaning, transforming, and preparing the data for machine learning model development.

3. **Feature Engineering**: Selecting, creating, or modifying features to enhance model performance.

4. **Model Development**: Implementing and comparing various regression algorithms to predict house prices effectively.

5. **Model Evaluation**: Assessing model performance using appropriate metrics and techniques.

6. **Data Visualization**: Creating visual representations of the data and model predictions to aid interpretation and presentation.

7. **Insights and Recommendations**: Drawing conclusions and providing actionable recommendations based on the analysis.

## Findings and Conclusion

### Data Exploration Findings

During the data exploration phase, we made several key findings:

- **Feature Correlations**: We identified strong correlations between house prices and specific features, such as square footage and the number of bedrooms and bathrooms.
  
- **Location Matters**: Location plays a significant role in house prices, with certain neighborhoods showing higher average prices than others.

- **Condition Influence**: The overall condition of a house also influences its price, with well-maintained properties commanding higher prices.

### Data Preprocessing Insights

In the data preprocessing phase, we addressed various challenges:

- **Handling Missing Data**: We employed strategies to deal with missing data, including imputation and, where appropriate, removal of rows or columns.

- **Outlier Detection**: We identified and addressed outliers that could potentially skew our model's predictions.

### Model Development and Evaluation

We experimented with several regression algorithms, including Linear Regression, Decision Trees, and Random Forests, to predict house prices. Here are some key outcomes:

- **Model Comparison**: We compared the performance of these models using metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

- **Random Forest Success**: The Random Forest regression model outperformed other models, demonstrating its effectiveness in predicting house prices.

### Data Visualization

We used data visualizations to enhance our understanding of the dataset and model predictions. Some notable visualizations include:

- **Feature Importance Plot**: A visual representation of the most influential features in predicting house prices.

- **Residual Plots**: Visualizing model residuals to check for patterns and heteroscedasticity.

# <img src="https://www.getcloudapp.com/wp-content/uploads/2021/03/5aebb952e4867ce13f4d308f_laptop_gif_trans.gif" > Screenshots
*This graph shows distribution of categorical variables through Heatmap.*
![image]![histogram1](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/a4f1cd0c-5bf4-4ae6-8e61-cd8fddf36a91)
![image]![histogram2](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/38aef265-90ef-4368-abca-a550bde28a66)
![image]![histogram4](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/6e994e40-0989-4f12-ba35-b7ade1e81417)
![image]![histogram3](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/7728694c-69b0-4666-9181-053167e20c9f)

*This graph isualize the correlations between all the variables through Pair Plot.*
![image]![plot pair](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/4c9028b8-5ea1-4182-a9cf-e20ef8fd9126)

*The below correlation table provides a summary of correlation between continuous variable in data through Heat Map.*
![image]![heatmap](https://github.com/goldenbkj1/House-Sales-In-King-County-Regression/assets/114793267/b74d1f58-e3ef-4d2b-b555-b9f849f8e460)








### Conclusion

In conclusion, our machine learning models provide valuable insights into predicting house prices in King County. We found that factors such as square footage, location, and overall condition significantly impact house prices.

The Random Forest regression model, in particular, proved to be the most accurate in predicting house prices, offering a valuable tool for prospective buyers and sellers in the King County housing market.

### Future Directions

While we have achieved success in predicting house prices, there are opportunities for further improvement:

- **Feature Engineering**: Exploring additional features or engineering new ones to enhance model performance.

- **Advanced Algorithms**: Investigating more complex machine learning algorithms for even more accurate predictions.

- **Real-time Updates**: Implementing real-time data updates to keep our predictions current.

## Challenges Faced

1. **Model Selection:** Explored models like Linear Regression, Decision Trees, Random Forest, and SVR, highlighting their unique strengths and weaknesses for house price prediction.

2. **Time Management:** Implemented effective project timelines with milestones, ensuring efficient allocation of time across data preprocessing, modeling, and evaluation.

3. **Library Usage:** Leveraged Pandas, Scikit-Learn, Matplotlib, and Seaborn for streamlined data manipulation, modeling, and visualization. Efficient use and documentation of libraries improved workflow and collaboration, a crucial aspect of successful data science projects.

## Dataset

The dataset used for this project is the [KC House Data](https://www.kaggle.com/datasets/shivachandel/kc-house-data) available on Kaggle. It includes a wide range of information about houses in King County, Washington, including features such as square footage, number of bedrooms and bathrooms, location, condition, and more. The dataset also contains information on the sale prices of these houses.
