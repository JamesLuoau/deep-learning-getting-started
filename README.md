# deep-learning-getting-started
BGL Developer Internal Training Project

Every equation in the book, the readership would be halved
[<A Brief History of Time>](https://en.wikipedia.org/wiki/A_Brief_History_of_Time)

##Linear Regression


##Logistic Regression among discrete classes


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