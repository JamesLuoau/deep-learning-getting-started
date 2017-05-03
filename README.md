# deep-learning-getting-started
BGL Developer Internal Training Project

Every equation in the book, the readership would be halved
[<A Brief History of Time>](https://en.wikipedia.org/wiki/A_Brief_History_of_Time)

##How would you going to implement it?
If?
Thousands of if?
100 thousands of if?


##Brain

##What makes you and me
Kids brain formed, 3 or 8 years old we got the highest neural in our head

##If we'd like to save our brain, what format is it going to have?
Text?
Pictures?
Videos

##What dose weights means
![Linear Regression](pictures/logistic_regression_uni.png)

![Linear Regression Gradient Descent](pictures/logistic_regression_minimize_error_and_gradient_descent.png)

![Linear Regression And Table](pictures/one_and_table.png)

[Source for And Preceptron](one_perceptron_and.py)

##How to find the right weights
![Gradient Descent](pictures/gradient_descent.png)

##Expend weights to multiple level
![Multiple Layer](pictures/multilayer-diagram-weights.png)

![Input Times Weights](pictures/input-times-weights-dots.png)


##Neural Network Structure
A Neural Network have to have a training and prediction process, we make two method
```python
def train(x, y):
    pass
    
def predict(x):
    y = None
    return y
```

###Node
```python
def sigma_summation(x, weights):
    sum([xi + wi for xi in x for wi in weights])
```

####Activation Functions
we have many activation functions, but only two things we really care about which is 
equation and derivation

You can [view activation functions here](https://en.wikipedia.org/wiki/Activation_function)

```python
class ActivationFunc(object:
    def __init__(name, equation, derivation):
        pass
```

###Training Process
1. Init weights
```python
def initilise_weights():
    pass
```