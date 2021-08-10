## What is Machine Learning?

Two definitions of Machine Learning are there

* Arthur Samuel described it as: "**the field of study that gives computers the ability to learn without being explicitly programmed.**" This is an older, informal definition.

* Tom Mitchell provides a more modern definition: "**A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E**".
  
>Example
    1.**playing checkers**
    E = the experience of playing many games of checkers
    T = the task of playing checkers.
    P = the probability that the program will win the next game
    2.**The process of the algorithm examining a large amount of historical weather data**
    T := The weather prediction task.
    P := The probability of it correctly predicting a future date's weather.
    E := The process of the algorithm examining a large amount of historical weather data.

## Major Classifications In Machine Learning:

* Supervised learning 
  
* Unsupervised learning
  
## 1. Supervised Learning:

*_we are given a data set and already know what our correct output should look like, having the idea that there is a relationship between the input and the output_*.

* Simply given data is having labels

Further Supervised Learning classified into two types :
They are

### 1) Regression Problem

we are trying to predict results within a continuous output, meaning that we are trying to map input variables to some continuous function.

  * Simply working with Continuous valid output


### 2) Classification Problem : 

we are instead trying to predict results in a discrete output. In other words, we are trying to map input variables into discrete categories. 
    * simply we have to classify the dataset according to the features they have

### Examples:

1)  
   * Given data about the size of houses on the real estate market, **try to predict their price**. Price as a function of size is a continuous output, so this is a regression problem.
   * We could turn this example into a classification problem by instead making our output about whether the house **sells for more or less than the asking price**. Here we are classifying the houses based on price into two discrete categories.

2) 
    * Regression - Given a picture of a person, we have to **predict their age on the basis of the given picture**
    * (b) Classification - Given a patient with a tumor, we have to **predict whether the tumor is malignant or benign**.
  
## 2. Unsupervised Learning

* Unsupervised learning allows us to approach problems with little or no idea what our results should look like. We can derive structure from data where we don't necessarily know the effect of the variables.
  
* We can derive this structure by **clustering** the data based on relationships among the variables in the data.
  
### Examples

#### Clustering

* Take a collection of 1,000,000 different genes, and find a way to automatically group these genes into groups that are somehow similar or related by different variables, such as lifespan, location, roles, and so on.

#### Non-clustering

* The "Cocktail Party Algorithm", allows you to find structure in a chaotic environment. (i.e. identifying individual voices and music from a mesh of sounds at a cocktail party).
  
## Linear Regression with One Variable :


* Cost Function is called as Squared Error Function


    $$ J(θ_0,θ_1) = \frac{1}{2m} ∑^m _i(h_θ​(x_i​)−y_i​)^2 $$
    * i = 0 
