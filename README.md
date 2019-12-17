
# Object Initialization - Lab

## Introduction
In this lab, you'll practice defining classes with `__init__` methods. You'll define two classes, `Driver` and `Passenger` in the cells below. 

## Objectives

In this lab you will:

* Create instance variables in the `__init__` method
* Use default arguments in the `__init__` method  

## Initializing Instance Objects

Start off by defining the `Driver` class, similar to as you've done before. This time, define an `__init__` method that initializes a driver with the attributes `first`, `last`, and `occupation` for their first name, last name, and occupation. Provide a default argument of `"driver"` for `occupation`.


```python
# Define Driver class here
```

Now, initialize a driver with the first name `"Dale"` and last name `"Earnhardt"`.

<img src="images/dale.gif" width="500">

gif from [Nascar](https://giphy.com/nascar)


```python
dale_earnhardt = None # Initialize Dale Earnhardt here
print(dale_earnhardt.first) # "Dale"
print(dale_earnhardt.last) # "Earnhardt"
print(dale_earnhardt.occupation) # "driving"
```

Next, define the `Passenger` class. Using the `__init__` method, ensure all instances contain the attributes `first`, `last`, `email`, and `rides_taken` for their first name, last name, email, and number of rides they have taken. Provide the `__init__` method with the default argument of `0` for the `rides_taken` attribute since new passengers should not have taken any rides. 


```python
# Define Passenger class here
```

Now that you've defined a `Passenger` class, check it out by initializing a new passenger with the first name `"Jerry"`, the last name `"Seinfeld"`, and the email `"jerry.seinfeld@mailinator.com"`.


```python
jerry = None # Initialize Mr. Seinfeld here
print(jerry.first) # "Jerry"
print(jerry.last) # "Seinfeld"
print(jerry.email) # "jerry.seinfeld@mailinator.com"
print(jerry.rides_taken) # 0
```

Great work! Mr. Seinfeld is now in the system and ready to request a ride!

## Summary


In this lab, you defined `__init__` methods that allowed you to initialize new instances with a set of predetermined attributes and default attributes.
