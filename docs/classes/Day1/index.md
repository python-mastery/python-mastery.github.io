# Codes and contents for the Day 1 class

## Variables and Data Types

This section covers the basics of variables and data types in Python.
Some of the data types are:

`Integer`, `Float`, `String`, `Boolean`, `List`, `Tuple`, `Dictionary`

`Integer` is a whole number, like `4`, `5`, `6`.

`Float` is a decimal number, like `4.5`, `5.6`, `6.7`.

`String` is a sequence of characters, like `"Hello"`, `"World"`.

`Boolean` is a value that can be either `True` or `False`.

`List` is a collection of items, like `[1, 2, 3]`, `["apple", "banana", "cherry"]`.

`Tuple` is a collection of items, like `(1, 2, 3)`, `("apple", "banana", "cherry")`.

`Dictionary` is a collection of key-value pairs, like `{"name": "Asib", "age": 21}`.



```python title="variables_and_data_types.py" linenums="1"
a = 4   #(1)
b: int = 5  #(2)
name = "Muhammad"   #(3)
age = 25    #(4)
height = 1.89   #(5)
is_married = True   #(6)
```

1. Integer variable
2. Integer variable with type annotation
3. String variable
4. Integer variable
5. Float variable
6. Boolean variable

## String Formatting and Printing

```python title="string_formatting_and_printing.py" linenums="1"
name = "Muhammad"
age = 25
height = 1.89
is_married = True

print(f"My name is {name}. I am {age} years old. And I am {height} meters tall.")    #(1)
print("My name is {}. I am {} years old. And I am {} meters tall.".format(name, age, height))   #(2)
print("My name is ", name, "I am ", age, "years old.")      #(3)
print("My name is " + name + ". " + "I am " + str(age) + "years old.")      #(4)
```

1. String formatting with f-string
2. String formatting with format method
3. String concatenation with comma without type casting
4. String concatenation with + operator with type casting

## Type Casting or Converting Data Types

```python title="type_casting.py" linenums="1"
a = "10"
b = int(a)    #(1)
print(b)
```

1. Type casting from string to integer

## List Operations

### List Creation

```python title="list_creation.py" linenums="1"
names = ["Asib", "Khalid", "Bappy"]
data = ["Asib", 21, "Khalid", 25, "Bappy", 22]
```

### List Accessing from index

```python title="list_indexing.py" linenums="1"
print(names[0])    #(1)
print(data[2])    #(2)
```

1. 'Asib'
2. 'Khalid'

### List Slicing

```python title="list_slicing.py" linenums="1"
asibs_data = data[:2]    #(1)
khalids_data = data[2:4]    #(2)
random_data = data[3:]    #(3)
```

1. ['Asib', 21]
2. ['Khalid', 25]
3. ['Bappy', 22]

### List Modification

```python title="list_copying.py" linenums="1"
asibs_data[1] = 22    #(1)
data[3] = 26    #(2)
```

1. Modifying the value of index 1
2. Modifying the value of index 3

### List Copying
The script demonstrates two methods for copying lists:
- Using `list()` function: `data2 = list(data)`
- Using slicing: `data3 = data[:]`

```python title="list_copying.py" linenums="1"
data2 = list(data)    #(1)
data3 = data[:]    #(2)
```

1. Copying the list using list() function
2. Copying the list using slicing
