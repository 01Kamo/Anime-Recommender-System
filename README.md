# Unsupervised-Learning-Recommender system
✨ Unveiling Anime Magic with Unsupervised Learning! ✨ Join our team as we explore the enchanting world of Anime using cutting-edge unsupervised learning techniques. 🌟


<div id="main image" align="center">
  <img src="https://images.squarespace-cdn.com/content/v1/57825361440243db4a4b7830/1656915345343-CX1U062QNY1LAXM47KE3/55794e9f617740728f0181d7a5bab0f3.jpeg" width="960" height="500" alt=""/>
</div>

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. MLFlow](#mlflow)
* [6. Streamlit](#streamlit)
  

## 1. Project Overview <a class="anchor" id="project-description"></a>
Build a collaborative and content-based recommender system for a collection of anime titles, capable
of accurately predicting how a user will rate an anime title they have not yet viewed, based on their
historical preferences.

The anime industry has experienced significant growth and popularity over the past few decades, with new series and seasons being released constantly. Today, the global anime market is estimated to be worth billions, with fans from all over the world enjoying a wide range of genres, from action-adventure to romance to science fiction. As the anime industry continues to evolve, there is an increasing demand for personalized content recommendations. Fans are looking for new shows that match their interests and tastes, and streaming platforms are scrambling to provide them with tailored suggestions. However, current recommendation systems often rely on basic algorithms that fail to account for the complexity and nuances of human preferences.

Problem Statement
With over 1,000 new anime shows released every year, it's increasingly difficult for fans to find new and exciting content that matches their individual tastes. Current methods of discovery, such as browsing through lists of recommendations or scrolling through social media, are often time-consuming and hit-or-miss. As a result, many fans end up stuck in a rut, watching the same familiar shows or struggling to find new content that resonates with them.

Aim
Our aim is to develop a highly accurate and user-centric recommender system that consistently provides fans with relevant and engaging anime recommendations, driving user engagement, retention, and satisfaction.

Objectives
Develop the Fusion-X Network app using Streamlit, allowing users to interact with the recommender system and explore anime shows in a seamless and engaging way.
Develop a recommender system that can accurately recommend shows that users will enjoy, based on their viewing history, ratings, and preferences.
Design a scalable recommender system that can handle a large volume of user data and content information, ensuring seamless performance even during peak usage.
Select and implement one of the three recommended models that best suits the needs of the Fusion-X Network recommender system, and evaluate its performance using Root Mean Square Error(RMSE).


## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset consists of thousands of users and thousands of anime titles, gathered from myanimelist.net.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```
## 5. MLFlow<a class="anchor" id="mlflow"></a>

MLOps, which stands for Machine Learning Operations, is a practice focused on managing and streamlining the lifecycle of machine learning models. The modern MLOps tool, MLflow is designed to facilitate collaboration on data projects, enabling teams to track experiments, manage models, and streamline deployment processes. For experimentation, testing, and reproducibility of the machine learning models in this project, you will use MLflow. MLflow will help track hyperparameter tuning by logging and comparing different model configurations. This allows you to easily identify and select the best-performing model based on the logged metrics.

- Please have a look here and follow the instructions: https://www.mlflow.org/docs/2.7.1/quickstart.html#quickstart

## 6. Streamlit<a class="anchor" id="streamlit"></a>

### What is Streamlit?

[Streamlit](https://www.streamlit.io/)  is a framework that acts as a web server with dynamic visuals, multiple responsive pages, and robust deployment of your models.

In its own words:
> Streamlit ... is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

> It’s a simple and powerful app model that lets you build rich UIs incredibly quickly.

[Streamlit](https://www.streamlit.io/)  takes away much of the background work needed in order to get a platform which can deploy your models to clients and end users. Meaning that you get to focus on the important stuff (related to the data), and can largely ignore the rest. This will allow you to become a lot more productive.  





