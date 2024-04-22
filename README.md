# asgmt-3-programming-design-2024
Assignment 3: Programming Design 2024.

## 01. Define a class `Pet` which instantiates objects with 1 attribute `species` and 1 method `make_sound()`.

```python
class Pet:
    """
    >>> dog = Pet('Dog', 'Bark')
    >>> type(dog)
    '__main__.Pet'
    >>> dog.species
    'Dog'
    >>> dog.make_sound()
    'Bark'
    >>> kitty = Pet('Cat', 'Meow')
    >>> type(kitty)
    '__main__.Pet'
    >>> kitty.species
    'Cat'
    >>> kitty.make_sound()
    'Meow'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 02. Define a class `Hogwarts` which instantiates objects with 3 attributes `location`, `founders`, and `houses`.

```python
class Hogwarts:
    """
    >>> hogwarts = Hogwarts()
    >>> type(hogwarts)
    '__main__.Hogwarts'
    >>> hogwarts.location
    'Scotland'
    >>> hogwarts.founders
    ['Godric Gryffindor', 'Salazar Slytherin', 'Rowena Ravenclaw', 'Helga Hufflepuff']
    >>> hogwarts.houses
    ['Gryffindor', 'Slytherin', 'Ravenclaw', 'Hufflepuff']
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 03. Define a class `StrCase` which instantiates objects with 3 methods `upper_case()`, `lower_case()`, and `swap_case()`.

```python
class StrCase:
    """
    >>> luke = StrCase('Luke Skywalker')
    >>> type(luke)
    '__main__.StrCase'
    >>> luke.upper_case()
    'LUKE SKYWALKER'
    >>> luke.lower_case()
    'luke skywalker'
    >>> luke.swap_case()
    'lUKE sKYWALKER'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 04. Define a class `MethodCalculator` which instantiates objects with 4 methods `add()`, `substract()`, `multiply()`, and `divide()`.

```python
class MethodCalculator:
    """
    >>> method_calculator = MethodCalculator(5, 6)
    >>> type(method_calculator)
    '__main__.MethodCalculator'
    >>> method_calculator.add()
    11
    >>> method_calculator.subtract()
    -1
    >>> method_calculator.multiply()
    30
    >>> method_calculator.divide()
    0.8333333333333334
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 05. Define a class `SymbolicCalculator` which instantiates objects with 1 method `calculate()`.

```python
class SymbolicCalculator:
    """
    >>> symbolic_calculator = SymbolicCalculator(5, 6)
    >>> type(symbolic_calculator)
    '__main__.SymbolicCalculator'
    >>> symbolic_calculator.calculate('+')
    11
    >>> symbolic_calculator.calculate('-')
    -1
    >>> symbolic_calculator.calculate('*')
    30
    >>> symbolic_calculator.calculate('/')
    0.8333333333333334
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 06. Define a class `FizzBuzz` which instantiates objects with 2 methods `scalar_fizz_buzz()` and `range_fizz_buzz()`.

Source: <https://en.wikipedia.org/wiki/Fizz_buzz>

```python
class FizzBuzz:
    """
    >>> fizz_buzz = FizzBuzz()
    >>> type(fizz_buzz)
    '__main__.FizzBuzz'
    >>> fizz_buzz.scalar_fizz_buzz(2)
    2
    >>> fizz_buzz.scalar_fizz_buzz(3)
    'Fizz'
    >>> fizz_buzz.scalar_fizz_buzz(5)
    'Buzz'
    >>> fizz_buzz.scalar_fizz_buzz(15)
    'Fizz Buzz'
    >>> fizz_buzz.range_fizz_buzz(1, 6)
    [1, 2, 'Fizz', 4, 'Buzz']
    >>> fizz_buzz.range_fizz_buzz(11, 16)
    [11, 'Fizz', 13, 14, 'Fizz Buzz']
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 07. Define a class `Summation` which instantiates objects with 2 methods `total()` and `cumulative()`.

```python
class Summation:
    """
    >>> summation = Summation(1, 2, 3)
    >>> summation.total()
    6
    >>> summation.cumulative()
    [1, 3, 6]
    >>> summation = Summation(2, 3, 5)
    >>> summation.total()
    10
    >>> summation.cumulative()
    [2, 5, 10]
    >>> summation = Summation(2, 3, 5, 7, 11)
    >>> summation.total()
    10
    >>> summation.cumulative()
    [2, 5, 10, 17, 28]
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 08. Define a class `DaysOfWeek` which instantiates objects with 2 methods `get_name()` and `get_abbreviation()`.

```python
class DaysOfWeek:
    """
    >>> days_of_week = DaysOfWeek(0)
    >>> days_of_week.get_name()
    'Sunday'
    >>> days_of_week.get_abbreviation()
    'Sun.'
    >>> days_of_week = DaysOfWeek(1)
    >>> days_of_week.get_name()
    'Monday'
    >>> days_of_week.get_abbreviation()
    'Mon.'
    >>> days_of_week = DaysOfWeek(6)
    >>> days_of_week.get_name()
    'Saturday'
    >>> days_of_week.get_abbreviation()
    'Sat.'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 09. Define a class `Month` which instantiates objects with 2 methods `get_name()` and `get_abbreviation()`.

```python
class Month:
    """
    >>> month = Month(1)
    >>> month.get_name()
    'January'
    >>> month.get_abbreviation()
    'JAN'
    >>> month = Month(2)
    >>> month.get_name()
    'February'
    >>> month.get_abbreviation()
    'FEB'
    >>> month = Month(3)
    >>> month.get_name()
    'March'
    >>> month.get_abbreviation()
    'MAR'
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```

## 10. Define a class `Palindrome` which instantiates objects with 2 methods `get_reversed_text()` and `is_palindrome()`.

Source: <https://en.wikipedia.org/wiki/Palindrome>

```python
class Palindrome:
    """
    >>> palindrome = Palindrome("yay")
    >>> palindrome.get_reversed_text()
    'yay'
    >>> palindrome.is_palindrome()
    True
    >>> palindrome = Palindrome("eye")
    >>> palindrome.get_reversed_text()
    'eye'
    >>> palindrome.is_palindrome()
    True
    >>> palindrome = Palindrome("day")
    >>> palindrome.get_reversed_text()
    'yad'
    >>> palindrome.is_palindrome()
    False
    >>> palindrome = Palindrome("dye")
    >>> palindrome.get_reversed_text()
    'eyd'
    >>> palindrome.is_palindrome()
    False
    """
    ### BEGIN SOLUTION
    
    ### END SOLUTION
```