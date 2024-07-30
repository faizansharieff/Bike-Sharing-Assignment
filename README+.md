# Bike Sharing Assignment
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Company's data of 2018 and 2019 is being used to solve this problem

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The comparison between the training and testing datasets reveals the following metrics for evaluating the regression model:
- The R-squared value for the training dataset is 0.837, indicating that approximately 83.7% of the variability in the bike demand can be explained by the independent variables in the model.

- The R-squared value for the testing dataset is 0.7958, suggesting that around 79.58% of the variability in the bike demand is captured by the model on unseen data.

- The adjusted R-squared value for the training dataset is 0.834, which takes into account the number of predictors in the model, providing a more reliable measure of the model's goodness of fit.

- The adjusted R-squared value for the testing dataset is 0.790, reflecting the adjusted goodness of fit on unseen data. The demand of bikes is influenced by various factors such as year, holiday, temperature, windspeed, September month, presence of light snow/rain, misty conditions, and the seasons of spring, summer, and winter.

- These metrics and the specified independent variables provide insights into the performance of the regression model in predicting bike demand and highlight the key factors affecting it.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- 1. Programming Language and Environment
Python: Used for data analysis, model building, and visualization.
Jupyter Notebook: For interactive coding and documentation.
- 2. Data Manipulation and Analysis Libraries
pandas: For data manipulation and analysis, including data cleaning, merging, and handling.
numpy: For numerical computations and array operations.
- 3. Data Visualization Libraries
matplotlib: For creating static, interactive, and animated visualizations.
seaborn: For statistical data visualization, including regression plots.
- 4. Statistical Analysis and Modeling Libraries
scikit-learn: For implementing the Multiple Linear Regression model, as well as other machine learning techniques like data splitting, model evaluation, and metrics.
statsmodels: For detailed statistical analysis and regression model summary.
- 5. Additional Tools and Libraries
SciPy: For additional scientific and technical computing tasks.
joblib or pickle: For saving and loading machine learning models.
- 6. Integrated Development Environments (IDEs) and Code Editors
VS Code: If used for coding and script editing.
- 7. Version Control and Collaboration
Git/GitHub: For version control and collaboration.


## Acknowledgements

- Academic and Professional Support

Acknowledge all my professors, instructors, or supervisors who guided me, provided insights, or reviewed my work.

Thanks to my batchmates, teammates, or colleagues who worked along, offered suggestions, or collaborated on the assignment.


## Contact
Created by [@faizansharieff] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->