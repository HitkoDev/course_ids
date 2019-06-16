# Python programming language

## Basic characteristics

Python is an interpreted, dynamically typed, object-oriented programming language.

Advantages:

* Simple.
* Easy to learn.
* Extensive packages.
* Cross-platform.
* Free and open source.
* Large user base.

Disadvantages:

* Being interpreted results in slower execution.
* Dynamic typing can lead to errors that only show up at runtime.
* Less suitable for mobile development and mobile computing.
* Higher memory consumption, less suitable for memory-intensive tasks.
* Underdeveloped database access layers.

## Why Python?

The Python language is one of the two most popular languages for data science (the other being R). The two main reasons are:

* The advantages of Python fit the typical data science workflow and its disadvantages are not that deterimental to the data science workflow.
* Python has a large ecosystem of packages, libraries and tools for data science, some of which are discussed later in this chapter.

The typical data science workflow consists of acquiring and manipulating data and applying standard machine learning or statistical methods. In essence, the data flows through different methods. The emphasis is on obtaining results - extracting meaningful information from data.

The advantages of Python are extremely beneficial to such a workflow: Being simple, easy to learn and free, it is accessible to a larger user base, including users with little or no prior programming experience. Being an interpreted language (and straightforward piecewise execution through read-eval-print loop shells or REPL) makes Python very flexible - multiple alternatives can be explored and quick decisions made on how to procede, depending on intermediary results.

The disadvantages of Python are of minor consequence: The data science workflow is not time-critical - even an order-of-magnitude slowdown typically makes little difference. Code maintainability is less important - data science scripts are often short and discarded after use. Mobile development, mobile computing or enterprise-level database work are also not part of the typical data science workflow.


## Setting up

How to install Python?

https://www.python.org/downloads/

### Python IDE's {-}

IDLE, PyCharm, ??? (brief descriptions with advantages/disadvantages)


### Python ecosystem for Data Science {-}

The Python ecosystem of libraries, frameworks, and tools is large and ever-growing. Python can be used for web scraping, machine learning, general scientific computing, and many other computing and scripting uses.

Some of the most popular packages:

* **scikit-learn** - ???
* **Scipy** - ???
* **Matplotlib** - ???
* **Numpy** - ???
* ???

Some of the most popular tools:

* **TensorFlow** - Deep learning.
* ???

## Python in 15 minutes

### Hello world! {-}


```python
print("Hello World!")
```

```
## Hello World!
```

### Variables and types {-}

#### Numbers and basic operators {-}


```python
a = 3  
b = 2.5  
c = a + b 
c = a * b
c = a / b
```

#### Strings and concatenation {-}


```python
a = "data" 
b = 'science' # we can use double and single quotes
c = a + " " + b
print(c)
```

```
## data science
```

#### Boolean {-}


```python
a = True
b = False
```

#### Iterables: Lists, Tuples, Sets {-}


```python
a = [1, 2, 3]          # List  
a = (1, 2, 3)          # Tuple (immutable)
a = {"a", "b", "c"}    # Set
```

#### Dictionaries {-}


```python
dict = {
  "title": "Introduction to Data Science",
  "year": 1,
  "semester": "fall",
  "classroom": "P02"
}
dict["classroom"] = "P03" 
```

### String formatting {-}

???

### More operators {-}


```python
a = "a"
print((a in {"a", "b"} and True) or False)
```

```
## True
```

```python
print(not True)
```

```
## False
```

### Control flow {-}

#### If-then-else {-}


```python
a = 2  
if a > 1:  
    print('a is greater than 1')
elif a == 1:  
    print('a is equal to 1')
else:  
    print('a is less than 1')
```

```
## a is greater than 1
```


#### Loops {-}


```python
for i in range(4, 6):
    print(i)
```

```
## 4
## 5
```

```python
people_list = ['Ann', 'Bob', 'Charles']  
for person in people_list:
    print(person)
```

```
## Ann
## Bob
## Charles
```

```python
i = 1
while i <= 3:
  print(i)
  i = i + 1
```

```
## 1
## 2
## 3
```

### Functions

???

### Classes and objects

???


## Further reading and references

good books? references? online tutorials? quick reference sheets? anything that would help the students on the path to achieveing goals from previous section

* Python Tutorials: https://docs.python.org/3/tutorial/index.html

## Learning outcomes

Data science students should work towards obtaining the knowledge and the skills that enable them to:

* Use the Python programming language for common programming tasks, data manipulation, file I/0, etc.
* Identify the Python IDE(s) that best fit their requirements.
* Find suitable Python packages for the task at hand and use them.
* Recognize when Python is and when it is not a suitable language to use.


## Practice problems

some practice problems? (=homework)