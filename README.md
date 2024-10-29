# BoomBikes Case Study
> A study to analyze and predict bike-sharing demand using linear regression models.


## How to run project
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

```
jupyter notebook \
    --notebook-dir="." \
    --ip=0.0.0.0 --port=3225
```



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Project Overview**: The BoomBikes Case Study focuses on predicting the demand for shared bikes based on various features such as weather, time, and season. We use multiple linear regression techniques to identify the most significant variables affecting bike demand.
- **Business Problem**: Due to the ongoing pandemic, BoomBikes suffered dips in revenue. The goal of this project is to understand the demand for shared bikes and build a predictive model that can help strategize and accelerate revenue growth.
- **Dataset**: The dataset used for this project contains information about daily bike rental counts, including various meteorological and seasonal factors. It includes data on temperature, humidity, weather situation, working day, season, and more.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- **Season and Weather Impact**: Bike rental demand is significantly influenced by the season and weather situation. Demand is higher in pleasant weather and during favorable seasons (`season_3` and `season_4`).
- **Temperature Correlation**: Temperature (`temp`) has a strong positive correlation with bike rental demand, indicating higher rentals in warmer weather.
- **Impact of Year**: Demand increased significantly in the second year (`yr`), indicating that bike-sharing systems gained more popularity over time.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- **Python** - Version 3.x
- **Jupyter Notebook** - For running and documenting the analysis
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Statsmodels & Scikit-Learn** - Building linear regression models


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

 

## Contact
Created by [@jafarijason](https://github.com/jafarijason) - feel free to reach out for collaboration or further inquiries.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/jasonjafari/).


## Additional Resources
- [Jupyter Notebook](https://github.com/jafarijason/ds_002_boom_bikes_case_study_regression/blob/master/Group_Facilitator_Jason_Jafari.ipynb)
- [Answering Subjective Questions](https://github.com/jafarijason/ds_002_boom_bikes_case_study_regression/blob/master/Regression%2BSubjective%2BQuestions.pdf)