## Description

This repository contains the data query (preprocessing) and the data visualization sections of the project.

## Data Query

The data was directly downloaded from kaggle www.kaggle.com. The following steps show the querying process.

### Step 1

Go to www.kaggle.com. Click **Sign in** or **Register**.

<img src="Step1.png" alt="Step1">

### Step 2

After successfully logging into kaggle, go to https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention.
<img src="Step2.png" alt="Step2">

### Step 3

Click **Download(89kb)**.
<img src="Step3.png" alt="Step3">

### Step 4

A file named **archive.zip** will be downloaded. UnZip it. There will be a file named **dataset.csv**.

<img src="Step4-1.png" alt="Step4-1">

<img src="Step4-2.png" alt="Step4-2">

## Data Preprocessing

We are using One-hot encoding for the data preprocessing.
One-hot encoding preserves the categorical information in a way that prevents the model from assuming any ordinal relationships between the categories. Each category is treated as a distinct and independent entity. When dealing with categorical variables without one-hot encoding, some algorithms may mistakenly assume an inherent order or numerical relationship between categories. One-hot encoding helps avoid such biases in model interpretation.
And since there we are predicting student academic success/failure (dropout), we will provide a optional section for selecting the necessary **Target**.

<img src="Pseudocode.png" alt="Pseudocode">

## Data Visualization

It's recommended to use the following google colab link to visualize data by showing the relationship between variables.

https://colab.research.google.com/drive/1sOyhy07Wqr4DO9uS9iq0C0q5Q9HYoWwU?usp=sharing

Please change the following into the specific variables you would like to visualize. In this example, it shows relationship between Course and GDP.

<img src="Instruction.png" alt="Instruction">
