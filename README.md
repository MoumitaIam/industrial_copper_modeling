# Industrial Copper Modeling: Machine Learning Models for Copper Industry

## Introduction

This project aims to develop two machine learning models for the copper industry to address the challenges of predicting the selling price and lead classification. Manual predictions can be time-consuming and may not result in optimal pricing decisions or accurately capture leads. The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and leveraging tree-based models, specifically...

## Regression Model Details

The copper industry deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing decisions. A machine learning regression model can address these issues by utilizing advanced techniques such as:

- Data normalization
- Outlier detection and handling
- Handling data in the wrong format
- Identifying the distribution of features
- Leveraging tree-based models, specifically the decision tree algorithm.

This regression model will predict the continuous variable **'Selling_Price'**.

## Classification Model Details

Another area where the copper industry faces challenges is in capturing the leads. A lead classification model is a system for evaluating and classifying leads based on how likely they are to become a customer. In this case, we will use the **STATUS** variable, with **WON** being considered as Success and **LOST** as Failure. Data points other than **WON** and **LOST** will be removed to ensure clean data for classification.

This classification model will predict the **Status** as **WON** or **LOST**.

## Solution

The solution includes the following steps:

1. **Exploring skewness and outliers** in the dataset.
2. **Transforming the data** into a suitable format and performing necessary cleaning and pre-processing steps.
3. Developing a **machine learning regression model** that predicts the continuous variable **'Selling_Price'** using the **decision tree regressor**.
4. Developing a **machine learning classification model** that predicts the **Status: WON** or **LOST** using the **decision tree classifier**.
5. Creating a **Streamlit app** where you can insert each column value and get the predicted **Selling_Price** or **Status** (WON/LOST).

## Requirements

This project requires the following libraries to be installed:

- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Streamlit**

To install these libraries, you can use the following:

```bash
pip install numpy pandas scikit-learn streamlit
