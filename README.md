# Life expectany index prediction 💡
This project focuses on developing a polynomial regression model trained on a dataset that encompasses various metrics from multiple countries across different years. Specifically, the model aims to predict the life expectancy index of a given country based on several predictive features, including GDP, Body Mass Index (BMI), and health indicators related to prevalent diseases. The goal is to utilize these features to estimate life expectancy with a high degree of accuracy, providing valuable insights into how economic and health-related factors influence longevity.
<br>
<br>



<h3 align="left">Datasets:</h3>
<p>
  We have two datasets, the first one is the <code>train</code> dataset and the second one is <code>test</code> dataset which has the same dataset with train except it
doesn't have label (life expectancy). Our train dataset contains 18 columns, in which the first 17 columns are the features and the last column
is the label. Furthermore, the features presented in the dataset represent some characterisics about a country in a specific year. For instance, 
the model will use <code>GDP</code> (gross domestic product) or <code>BMI</code> (body mass index) as effective features to predict the life expectancy index.
</p>


<br>
<br>

<h3 align="left">Model and evaluation:</h3>
In this project, we will use <code>polynomial regression</code> model which is provided by <Code>Scikit-Learn</Code> library. In addition, the model will be evaluated
by <code>r2-score</code> criteria which is also exists in <Code>Scikit-Learn</Code>.

<br>
<br>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>


