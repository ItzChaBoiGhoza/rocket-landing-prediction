# SpaceX Launch Insights 🚀

Data analysis and machine learing project predicting SpaceX first stage reuse and estimating launch costs using SpaceX launch data.

## 📌 Project Overview
This project was completed as part of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science). The objective of this project is to apply end-to-end data science skills, from data collection and wrangling to analysis , visualization, and building machine learning models.

## 🎯 Objectives
- Collect and clean data from sources.
- Perform exploratory data analysis (EDA) and visualization.
- Apply clustering and/or predictive modeling techniques.
- Communicate results through visualizations and a final report.

## Tools & Technologies
- **Python**: Pandas, Numpy, Scikit-learn, Matplotlibm Seaborn, Folium
- **Environment**: Jupyter Notebook

## 📈 Results
After model training, the result shows that Decision Tree got the highest training accuracy (0.89), meanwhile K-Nearest Neighbor got the lowest accuracy (0.8). But, when given unseen test set, Logistic Regression and SVM got the highest accuracy of (0.94) showing that they are able to adapt to new data. Despite the Decision Tree having the highest accuracy on training data, it has the lowest test accuracy with (0.83) suggesting a little overfitting.

In simple way, the training results suggest that the dataset benefit more with simpler linear models like Logistic Regression and SVM, while the other models like Decision tree based might require more tuning to avoid overfitting.

## 🏃 How to Run
1. Clone this repository:
```
git clone git@github.com:ItzChaBoiGhoza/rocket-reuse-prediction.git
```
2. Navigate into the project folder:
```
cd rocket-reuse-prediction
```
3. Open Jupyter Notebook and run the notebooks step-by-step:
```
jupyter notebook
```

## 🙏 Acknowledgement
This project is part of the [IBM Data Science Professional Certificate Capstone](https://www.coursera.org/learn/applied-data-science-capstone?specialization=ibm-data-science) program on Coursera. The problem statement and initial guidance were provided by IBM. The implementation, analysis, and any additional extensions in this repository are my own. 
