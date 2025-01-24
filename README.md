TasteCraft: Enhancing Food Flavor Profiles through Data-Driven Innovation

Project Description:
"TasteCraft" leverages advanced data science techniques to enhance food flavor profiles in the Food and Beverage industry. 
By analyzing sensory data, ingredient compositions, and consumer feedback, the project identifies critical factors 
influencing taste. This enables actionable insights for improving product formulation and elevating customer satisfaction.

Table of Contents:
1. [Problem Statement](#problem-statement)
2. [Abstract](#abstract)
3. [Data Collection](#data-collection)
4. [Feature Engineering](#feature-engineering)
5. [Modeling](#modeling)
6. [Model Evaluation](#model-evaluation)
7. [Conclusion](#conclusion)
8. [References](#references)

Problem Statement:
The Research and Development department in the Food and Beverage industry faces challenges in understanding factors 
influencing food taste. This project aims to use machine learning models like Linear Regression, Support Vector Machines 
(SVM), and Random Forest Regression to analyze data and provide actionable recommendations for enhancing flavor profiles.

Abstract:
This project dissects the intricacies of food taste through data-driven methodologies. Using machine learning models and a 
robust feature engineering process, we explore factors such as flavor intensity, texture complexity, and aroma richness. The 
insights generated will improve product quality and customer satisfaction, ultimately strengthening the organization's 
competitive edge.

Data Collection:
Data was collected from various web resources and includes the following features:
- Ingredient composition
- Cooking time and temperature
- Texture and mouthfeel
- Spices and herbs
- Aroma richness, among others.

"The dataset was manually created and formatted for analysis."

Feature Engineering:
Key engineered features include:
1. Flavor Intensity: Combines sweetness, saltiness, and umami intensity.
2. Texture Complexity: Reflects the diversity and complexity of food textures.
3. Spice Profile: Represents types and quantities of spices used.
4. Freshness Index: Indicates ingredient and dish freshness.
5. Culinary Technique Score: Evaluates cooking methods.
6. Aroma Richness: Measures the complexity of dish aroma.

Modeling:
Machine Learning Models:
1. Linear Regression: Captures linear relationships in the dataset.
2. Support Vector Machine (SVM): Handles high-dimensional data with kernel transformations.
3. Random Forest Regression: Captures non-linear relationships using ensemble methods.

Model Evaluation
The models were evaluated using:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- R² Score

Results:
| Model                  | MSE       | MAE       | RMSE      | R²      |
|------------------------|-----------|-----------|-----------|---------|
| Linear Regression      | 6.81e-29  | 6.57e-15  | 8.25e-15  | 1.0     |
| Support Vector Machine | 0.01      | 0.06      | 0.07      | 1.0     |
| Random Forest          | 0.0464    | 0.153     | 0.215     | 0.999   |

Conclusion:
All three models performed exceptionally well, with Linear Regression and SVM achieving near-perfect predictions. Random 
Forest Regression provided competitive results and demonstrated robustness in capturing complex patterns. The choice of the 
final model will depend on specific business requirements such as computational efficiency and interpretability.

References:
- [Matplotlib](https://matplotlib.org) – Data visualization
- [Pandas](https://pandas.pydata.org) – Data formatting
- [NumPy](https://numpy.org) – Numerical computations
- [Seaborn](https://seaborn.pydata.org) – Advanced visualization
- [Scikit-learn](https://scikit-learn.org) – Machine learning models

Colab Notebooks:
- [Notebook 1](https://colab.research.google.com/drive/1KIYzNSC-fNTM3LpjTn_LR9GOfsDSsh5M)
- [Notebook 2](https://colab.research.google.com/drive/1bP63go-M911zAxueDBrYk3apteTUKjF7)
- [Notebook 3](https://colab.research.google.com/drive/1bP63go-M911zAxueDBrYk3apteTUKjF7 )
