# Phase3-data-analysis

\# SyriaTel Customer Churn Prediction



\## Overview



This project focuses on building a machine learning classifier to predict whether a customer will soon stop doing business (churn) with SyriaTel, a telecommunications company. Churn prediction is essential for reducing customer loss and optimizing business strategies.



The target audience for this project is SyriaTel and other stakeholders interested in improving customer retention and reducing revenue loss due to churn.



---



\## Repository Structure



```

├── data/                    # Contains dataset(s) used

├── notebooks/               # Jupyter notebooks for exploration, modeling, evaluation

├── models/                  # Saved models and performance reports

├── visuals/                 # Plots and visualizations

├── README.md                # Project overview and instructions

├── presentation.pdf         # Final presentation

```



---



\## Project Summary



\### Problem Type



\- Binary Classification: Predict whether a customer will churn (Yes/No)



\### Data Science Steps Followed:



1\. \*\*Data Loading and Cleaning\*\*

2\. \*\*Exploratory Data Analysis (EDA)\*\*

3\. \*\*Feature Selection \& Engineering\*\*

4\. \*\*Model Training and Evaluation\*\*

5\. \*\*Model Comparison\*\*

6\. \*\*Insights and Business Recommendations\*\*



\### Models Implemented



\- Logistic Regression

\- Random Forest Classifier

\- Lasso Regression

\- Decision Tree Classifier



---



\## Key Takeaways



\### Performance Comparison



| Model               | Accuracy   | Precision | Recall   | F1-Score |

| ------------------- | ---------- | --------- | -------- | -------- |

| Logistic Regression | 85.31%     | 0.55      | 0.18     | 0.27     |

| Lasso Regression    | 84.86%     | 0.50      | 0.01     | 0.02     |

| Decision Tree       | 89.20%     | 0.80      | 0.40     | 0.53     |

| Random Forest       | \*\*93.55%\*\* | \*\*1.00\*\*  | \*\*0.57\*\* | \*\*0.73\*\* |



\### Highlights:



\- \*\*Random Forest\*\* had the best balance of precision, recall, and F1-score.

\- Logistic Regression missed 82% of actual churners.

\- Decision Tree helped visualize key decision paths and features.



---



\## Predictable Patterns



\### Top Features Associated with Churn:



\- \*\*Customer Service Calls\*\*: More calls indicate dissatisfaction and predict churn.

\- \*\*International Plan\*\*: Customers with this plan tend to churn more.

\- \*\*Voice Mail Plan\*\*: Similarly, having this plan correlated with higher churn.

\- \*\*Total Day Minutes\*\*: Higher usage is associated with more churn.



\### Decision Tree Insights:



\- Customers with low day minutes and fewer service calls were less likely to churn.

\- The decision tree revealed clear splits based on service plans and engagement metrics.



---



\## Business Recommendations



\### Targeted Retention



\- \*\*Use model outputs to flag high-risk customers\*\* and proactively offer tailored discounts, improved service, or plan adjustments.



\### Improve Customer Service



\- Reduce complaints by analyzing call logs and resolving issues quicker.



\### Restructure Plans



\- Reassess the appeal of international and voice mail plans, and tailor offerings based on satisfaction analysis.



\### Potential Churn Reduction:



\- Based on predictive precision, proactive strategies could reduce churn by up to \*\*57%\*\*, especially when targeting customers flagged by the Random Forest model.



---



\## How to Use the Repository



1\. Clone the repo:

&nbsp;  ```bash

&nbsp;  git clone https://github.com/your-username/syriatel-churn-prediction.git

&nbsp;  cd syriatel-churn-prediction

&nbsp;  ```

2\. Launch the notebook:

&nbsp;  ```bash

&nbsp;  jupyter notebook notebooks/Untitled7.ipynb

&nbsp;  ```

3\. Run each cell in sequence to:

&nbsp;  - Load the dataset

&nbsp;  - Train models

&nbsp;  - Visualize performance

&nbsp;  - Analyze feature importances



---



\## Resources



\- \[Dataset Source](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)

\- \[Final Presentation](./presentation.pdf)

\- \[Notebook File](./notebooks/Untitled7.ipynb)



---



\## Conclusion



Through this project, it successfully identified key churn indicators and evaluated multiple machine learning models. The \*\*Random Forest\*\* model stood out, offering actionable insights that SyriaTel can leverage to \*\*retain valuable customers\*\* and \*\*reduce churn-related losses\*\*.





