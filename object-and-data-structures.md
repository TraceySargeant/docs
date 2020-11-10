# Object and Data Structures

## Summery

### Data Types

| Name | Type | Description |
| :--- | :--- | :--- |
| Integers | int | Whole numbers, such as: `3 300 200` |
| Floating point | float | Numbers with a decimal point: `2.3 4.6 100.0` |
| Strings | str | Ordered sequence of characters: `"hello" 'Tracey' "2000"` |
| LIsts | list | Ordered sequence of objects `[10,"hello',200.3]` |
| Dictionaries | dict | Unordered Key:Value pairs: `{"mykey":"value","name":"Tracey"}` |
| Tuples | tup | Ordered immutable sequence of objects: `(10,"hello",200.3)` |
| Sets | set | unordered collection of unique objects: `{"a","b"}` |
| Booleans | bool | Logical value indicating `True` or `False` |

## Numbers

### Basic Math

```python
# Addition 
2+1

# Subtraction
2-1

# Multiplication
2*2

# Division
3/2

# Preposition (exponetials)
2 ** 3
```

#### Modulo or "Mod" operator

Gives the remainder of  7/4 

```python
# Give the remainder of 7/4
7 % 4

# Gives 0 (nothing left over)
50 % 5

#This results in 1, telling us it's odd
23 % 2
```

#### BODMAS





```python
# Result of 105
2 + 10 * 10 + 3

# Result of 156
(2 + 10) * (3 + 10)
```

## Variable Assignment

### Rules for variable names

* Names can not start with a number.
* There can be no spaces in the name, use \_ instead.
* Can't use any of these symbols :'`",<>/?|\()!@#$%^&*~-+`
* Best practice \(PEP8\) that names are lowercase
* Avoid using words that have special meaning in Python like "list" and "str"



### Dynamic Typing

* Python uses **Dynamic Typing** 
* This means you can reassign variables to different data types.
* This makes Python very  assigning data types, this is different than other languages that are **"Statically-Typed"** 

\*\*\*\*

#### **Example of Dynamic typing in Python**

```python
# Assigning a variable a different data type 
# (e.g from number to list)
# works in Python but not other languaes
my_dogs = 2
# Different data type
my_cats = ["Coco","Frosty"] 
```

#### Example of Static Typing \(C++\)

```cpp
int my_cat = 1;
my_cat = "Coco"; //results in error
```

### Pros of Dynamic Typing:

* Very easy to work with
* Faster development time

### Cons of Dynamic Typing:

* May result in bugs for unexpected data types!
* You need to be aware of **`type()`**

#### Assigning variables 

```python
# assign a as 5
a = 5

# take the current value of a 
# add it to itself and assign its new value
a = a + a
# see value is now 10
a

# assign newvalue
a = a + a 
# see the new value is now 20
a

# see that a is an int
type(a)
int

# assign a a new data type
a = 30.1 

# see that a is now a float
type(a)
float
```

#### Example of real-life variable assignment 

```python
# assignment
my_income = 100
tax_rate = 0.1
my_taxes = my_income * tax_rate

# outcome
my_taxes
10.0
```

## Strings

Strings are sequences of characters, using the syntax of either single quotes or double quotes:

* 'hello'
* "hello"
* "I don't do that"

### Basics

* Strings are **ordered sequences**, so we can use **indexing** and **slicing** to grab sub-sections of the srting.
* Indexing notation uses `[]` notation after the string \(or variable assigned to the string\).
* Indexing allows you to grab a single character from the string...
* These actions use `[]` square brackets and a number index to indicate positions of waht you wish to grab. 
  * **Character: h e l l o** 
  * **Index: 0 1 2 3 4**
  * **Reverse indexing: 0 -4 -3 -2 -1**
* Slicing allows you to grab a subsection of multiple characters, a "slice" of the string.
* This has the following syntax:
  * **\[start:stop;step\]**
* **start** is a numerical index for the slice start 
* **stop** is the index you will go up to \(but not include\)
* **step** is the size of the "jump" you take

#### Examples of strings

```python
"hello"
'helo'

# a space is equal to a character
'this is also a string'

# enclose in doubles if you have a single etc
"I'm going on a run"

print("hello")
hello

#print escaping a new line \
# n = new line 
print('hello /nworld')

#pring escaping a tab
print('hello /tworld')

#cheing the length of a string
len('hello')

#notice that the space counts
len('I am')
```

### Indexing and slicing with strings

#### Indexing example

```python
mystring = "Hello World"
#grab the H from Hello
mystring[0]

#grab the l from world
mystring[-2]
```

#### Slicing example

```python
mystring = 'abcdefghijk'

#slice from 3rd character to end (stop and step undefined)
mystring[2:]

#slice up to 4th character from beginning (start and step undefined)
mystring[:3]

# slice 4th and 6th charater
mystring[3:6]
'def'
#slice 1st and 3rd character
'bc'

#slice the string as a whole, valid syntax
mystring[::]

#slice in jumps of 2
mystring[::2]

#slice with start, stop and stem
#slice 3rd char up until 8th char (not including) in steps of 2
mystring[2:7:2]
'ceg'

#reverse the order of the text
mystring[::-1]
```

### String Properties and Methods

## Print Formatting with Strings

## Lists

## Dictionaries

## Tuples

## Sets and Booleans

## Files



