# LOGISTIC OPTIMIZATION FOR GOKADA
* (applying casual inference)

<img src="/data/sales.jpg" alt="isolated" width="1000" height="250"/>

This project aims to solve this problem by working on the company’s data to help it understand the primary causes of unfulfilled requests as well as come up with solutions that recommend drivers locations that increase the fraction of complete orders. Since drivers are paid based on the number of requests they accept, your solution will help Gokada business grow both in terms of client satisfaction and increased business.

# Objectives

<details open>
<summary> 1. Exploration of order fulfillment</summary>
<br>
 Exploratory data analysis is the lifeblood of every meaningful machine learning project. It helps us unravel the nature of the data and sometimes informs how you go about modeling. A careful exploration of the data encapsulates checking all available features, checking their interactions and correlation as well as their variability with respect to the target. 

 In this task, We explore the behaviour of orders. Our goal is to check how some measures such as rainy days and holidays affect the status of an order. And also check how variations of driver locations from trip start locations affect the optimal delivery of orders. 

 To achieve this goal, we need to first clean the data. The data cleaning process will involve building pipelines to detect and handle outlier and missing data. This is particularly important because you don’t want to skew our analysis. 

 After cleaning the data, visualizing various features and interactions is necessary for clearly communicating our findings. It is a powerful tool in the data science toolbox. Communicate the findings below via the necessary plots. These plots are presented in the [EDA.ipynb](https://github.com/Amanuel3065/causal_inference_delivery/blob/main/notebooks/EDA.ipynb) python notebook.

</details>

<details open>
<summary> 2. Casual learning</summary>
<br>
* draw casual graphs
* Train XGboost and RF ML models
</details>

<details open>
<summary> 3. Logistic optimization</summary>
<br>
* Integer programming optimization
</details>

# INSTALLATION GUIDE
* git clone https://github.com/Amanuel3065/casual_inference_delivery
* cd casual_inference_delivery
* pip install -r requirements.txt
**
