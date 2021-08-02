# Types #
Everything in python has a particular 'type', that is to say they hold a particular value.

Here are the types available in python

- strings - Represent alphanumeric pieces of text.
- numeric types
  - integer - Represents any whole number. 
  - float - Represents any decimal number accurate to 15 decimal places
  - complex - Represents a real part and an imaginary part.
- lists - Represents an ordered set of data.
- tuples - Represent an ordered set of data whose values cannot be changed.
- booleans - Represent either `True` or `False`
- dictionaries - Represents a map of keys to values.

strings, the numeric types and booleans are known as 'primitive types' and they are used in other objects as well. Lists, tuples and dictionaries are called complex types and we will discuss them in further detail in another section.

## Strings ##
Strings represent any alpha-numeric piece of text, which put simply means its text that contains letters and numbers.

Strings in python are either wrapped in single quotes `'` or double quotes `"`. For example, we can write either `"Hello World!"` or `'Hello World!'`. Another example of a string is `"password1234t3st"`.

## Numeric types ##

### Integers ###
They represent any whole number value like `123` or `24567686800`.

### Floats ###
They represent any number with a decimal point and is accurate upto 15 decimal points. Examples are `11.0` or `11.1234567`.

### Complex ###
They represent a real portion and an imaginary portion. For example `5 + 2j` where 5 and 2 is the real part and j is the imaginary part.

## Booleans ##
Booleans represent either a value of `True` or `False`. They are especially useful in checking conditions. More on that in the section on conditionals.

# The `type` function #
`type()` is a built-in python function to check the type of something. You can call it on any valid value and it will return a result

```py
type('Hello!') # becomes <class 'str'> when printed
type("World!") # also prints <class 'str'>

type(11)       # becomes <class 'int'>
type(11.0)     # becomes <class 'float'>
type(3 + 11j)  # becomes <class 'complex'>

type(True)     # becomes <class 'bool'>
type(False)    # becomes <class 'bool'>
```