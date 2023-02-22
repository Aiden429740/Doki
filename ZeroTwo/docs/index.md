# Home Page

Documentation on a Character using Classes and Functions in Python.

## Classes

What are classes?

Classes are a way to take a grouping of functions and data and place them inside a container so you can access them with the . (dot) operator. For example, if you have a class named MyClass, to access a function inside that class you type:

```python

MyClass.my_function()

```

Classes provide many benefits over functions, including:

* Namespacing your functions and data so you don't have to worry about naming conflicts.
* Providing a way to encapsulate data and functions together.
* Providing a way to inherit from other classes.

### Creating a Character

First, we need to create a Class with the name "Character":

```python

class Character:

```

Then we add the Init function to the class:

```python

def __init__(self):

    pass

```

The __ are used to tell Python that this is a special function. The init function is called when you create a new object from the class. The self parameter is a reference to the current instance of the class, and is used to access variables that belong to the class.

And the "pass" keyword is used to tell Python to do nothing. It is a placeholder for code that will be added later.

Now we want to add Health, Attack, and Defense to the Character class. Before we do though,
we'll make sure to add default values to each of them too:

```python

def __init__(self, health=100, attack=10, defense=10):

    self.health = health
    self.attack = attack
    self.defense = defense

```
