# Admission Prediction System

## 1. Problem Statement

We aim to visualize the various factors affecting a student's admission to US colleges. Additionally, we will build a predictive model to assess a student's eligibility based on previous years' scores, using a linear regression model to predict the chance of admission.

## 2. Introduction

#### 2.1 MOTIVATION

The pressure on students during the higher education application process is high. Our classifier intends to provide a tool for individuals to understand their likelihood of admission based on required inputs. The dataset used in our model training achieves a 97% accuracy, offering users insights into their chances for a particular university.

### 2.2 SIGNIFICANCE

Quantitative data plays a crucial role in admission decisions, especially factors like CGPA and GRE scores. Leveraging these scores for analysis can aid in understanding admission trends, assisting students in shortlisting universities efficiently. The predicted output provides a fair idea about a student's chances for admission.

#### 2.3 SCOPE AND APPLICATION

With a 97% accuracy in our model, this project has the potential to evolve into a user-friendly GUI. College administrators can efficiently filter student applications, saving time and energy. Students can gauge their standing in the competition, identify areas for improvement, and work towards their admission goals.

## 4. Implementation

#### 4.1 FRAMEWORK

We plan to create insightful visualizations using tools such as Plotly and Seaborn. These visualizations, including Bar, Hist, Pie, Join Plot, and Box charts, will provide users with a comprehensive understanding of the dataset. Key visualizations include:
1. Identifying the most common score ranges for GRE, TOEFL, and CGPA.
2. Analyzing relationships between each column.
3. Determining major factors influencing the chance of admission.

#### 4.2 MODEL

We will explore multiple models for predicting admission chances, including:
1. **Linear Regression:**
   - Models the relationship between two variables by fitting a linear equation to observed data. One variable is considered explanatory, and the other is dependent.
2. **Support Vector Machine (SVM):**
   - Utilizes kernels and sparse solutions for effective real-value function estimation.
3. **Extra Trees Regressor (Random Forest):**
   - Implements a meta estimator with randomized decision trees on various sub-samples to improve predictive accuracy and control overfitting.

