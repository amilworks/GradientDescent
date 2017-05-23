# Linear Regression using Gradient Descent

For all of you PSTAT 126 students out there, and, well, people who have taken a course on _Linear Regression_, here is an example of how to start expanding your theoretical knowledge horizon. This example requires you know some basic `Python`. If you don't know the basics, seriously ask yourself why you are here, why you still exist, and why you think you will learn from someone who sucks at `Java`. 

![](https://cloud.githubusercontent.com/assets/22850980/26349410/6b6e50e4-3f64-11e7-9b84-681241831615.gif)


## Plotting Points 

![](https://cloud.githubusercontent.com/assets/22850980/26348383/7117fec6-3f61-11e7-90ae-681a207da9b3.jpg)

Let's say we have some points on a graph and we want to fit a line through them. This is linear regression--modeling some points on a graph with a line. I know I sound redundant, but it is necessary. Forget about the data, I graphed whatever I could in R. We see that we could probably fit a line through these points, but let's make it hard on ourselves and use gradient descent to prove this phenomenon with some random data. 

## Our Data
The data we will be using is from a dataset with 2 columns and 150 rows. The first column is hours studied, and the second column is grades on that test. The question of significance is, __Do students who study more hours receive better test scores?__

## The Error Function

We will begin by defining an error function that measures how “good” a given line is. Remember, we are trying to fit a line of _best_ fit. Computing this function will return an error value based on how well the line fits our data. 

![Gradient](https://cloud.githubusercontent.com/assets/22850980/26348210/e2adb1b2-3f60-11e7-9d07-83b19b9a50fd.jpg)


## Finding the Minimum
Next, these two equations will give us a helping hand when attempting to find the minimum.


![Gradient](https://cloud.githubusercontent.com/assets/22850980/26347671/257eebca-3f5f-11e7-83e2-7eefd3cd9618.jpg)

## How to Run and Results
The easiest way to show you how to run the code is by showing. 


![](https://cloud.githubusercontent.com/assets/22850980/26349969/67bcb9fc-3f66-11e7-9c76-6f37fb4190b5.png)


## Inspiration and Documentation

__Gradient Descent Example__
* Huge thanks to Matt Nedrich for providing a detailed example of gradient descent for noobs. Check his Github out. I learned a ton with this example alone. 
