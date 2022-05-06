# RoadMap


The second assignment is a full-fledged project with expectations equivalent to professional levels. Thus, we will take a step-by-step approach to make sure that we establish everything carefully and in a very elaborate manner.


```diff
! Note:- Comments are very important in this premise. Meaningful comments that highlight both the logic of the code and the thought process behind it are necessary. Small findings like relationships within independent variables, etc. must also be reported through the comments.</font>
```

### 1. Setting up the research goals.

The first step is to identify the research goals of the project. The most basic requirement of the assignment is to predict the energy usage which is   a regression problem.

### 2. Retrieving the data
This involves importing the dataset correctly in the jupyter notebook that we will be using. As per the requirements of the assignment, this data is enough and another data set need not be consulted. However, it is essential to read the description of the dataset and gather some knowledge of the domain of the dataset i.e. capturing some insights of electricity units(in our case). Citation of the resources is important.

### 3. Data Preparation

The first step will be extracting the basic information about the dataset such as the number of columns, name of columns, and the type of data contained in the columns, to create a basic sketch or summary of the data. An integer column, for example, maybe be summarised as a column having data supposed between the ranges 10-100 and the mean to be 69.69. Each column (or at least most of them)must be summarised in the same manner.

The second step would be to look for values such as-
* Noise/Abrupt Values
* Outliers
* Missing Values
* Negative Values (could be covered in noise)

and then pre-processing the data to remove those undesired values. Then, we will go for feature-scaling.

```diff
! Note- Both the scaled and unscaled data will be used for training. Also, the type of scaling such as standardization/normalization, etc. will be identified and must be justified.
```
The last step would be to go for feature engineering (not sure if it would belong here or not). We will use at least two techniques for feature engineering and justify the final selected features through them. We could also integrate two or more columns that require us to have some basic information of how to do that, when to do that and how to justify that. This also requires some subject domain knowledge.

### 4. Data Visualization
This part requires some extra focus this time as seen in the previous assignment. I prefer going through the process below.

1. Plots between the target and the independent variable.
Every column must be plotted against the target column. As we have a regression problem this time, we would be able to use a wider variety of graphs and may be able to get better relationships amongst the variables. I propose to use at least two types of graphs and use both the types individually between all the independent variables and the target column. In simple words, we can have one set of bar graphs and another set of line graphs.
       
2. We need to create graphs between each column.
3. A heatmap to depict the correlation between all columns with one another and the target variable. If possible we can also use another type of graph for the same purpose.

```diff
! Note – We need to explain the relationships that we find out between columns during this process as comments. This is a very important step that must not be left out. We will establish one successful plotting and then talk about that before moving on to the next one.
```

### 5. Data Modelling
The original aim of the project will be implemented here. We need to train and test the dataset on various machine learning algorithms and also tune the hyper-parameters to alter the baseline models.

1. Firstly, we will segregate the dataset into training and validation datasets. Both, the scaled and unscaled data need to be used for this purpose.
2. Baseline models will be fitted and tested for both training and testing datasets to determine possible chances of under/overfitting as well as data leakage.
3. Hyper-parameters will be tuned using the GridSearch methods for ease.
4. We will use almost all metrics to determine the best models.

#### The algorithms to be used are:-
1. Linear Regression
2. Polynomial Regression
3. Decision Trees
4. Random Forest
5. Rule-Based Learning (Optional)
6. Neural Networks

The data-splitting techniques:-
    1. train_test_split
    2. k-Fold

```diff
! Note - We will make graphs of the performance of different models with different parameters which will justify the selection of our parameters. Each metric that we use will have its own graph but will be common to each technique. In simpler words, a single containing the accuracy with all techniques will be plotted and then another graph of recall values with all techniques will be created. This way we will have graphs equal to the number of metrics that we consider. Also, we need to write our justification for using or not using the particular technique. 
```

### 6. Performance Visualisation
We will take the ultimate model and create a separate section where we discuss and plot the performance of the model selected as the best one. At last, we will discuss the challenges faced, limitations, and the future scope of the assignment before entitling our names at the end of the assignment.

### Information to be cited

1.  The resources used to gather information about electrical usage.
2. Codes used from StackOverflow.
3. Articles about various algorithms or data modeling techniques.
