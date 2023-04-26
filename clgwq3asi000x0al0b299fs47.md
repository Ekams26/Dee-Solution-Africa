---
title: "Basics of F-strings in Python"
seoTitle: "Python F-strings"
datePublished: Tue Apr 25 2023 20:31:44 GMT+0000 (Coordinated Universal Time)
cuid: clgwq3asi000x0al0b299fs47
slug: basics-of-f-strings-in-python
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1682453730089/d146f13a-795e-4a30-8f3e-7485a8f81714.png
tags: python3, coding, codenewbies, python-beginner, f-string

---

F-strings are a feature in Python 3.6 and above that allows you to easily format strings. They are also known as "**formatted string literals**." The F-strings provide a concise and readable way to embed expressions inside string literals using a minimal syntax. In this article, we will cover the basics of F-strings and provide in-line code examples to help you understand them better.

### **Basic Syntax**

The basic syntax for an F-string is to prefix a string with the letter `f` or `F` and include expressions inside curly braces or placeholders `{}` within the string. Here is an example:

```python
name = "Adeolu"
age = 25
print(f"My name is {name} and I am {age} years old.") 

#Output: My name is Adeolu and I am 25 years old.
```

In the above example, we used an F-string to embed the variables `name` and `age` inside a string. The expressions within the curly braces`{}` are evaluated when you run the code, and their values are inserted into the string.

### Expression Evaluation

Python's eval() allows you to evaluate arbitrary Python expressions from a string-based or a compiled-code-based input. Inside the curly braces, you can include any valid Python expression. The expression is evaluated at runtime and its result is inserted into the string. Here are some examples:

```python
x = 10
y = 5
print(f"x + y = {x + y}")  # Output: x + y = 15
print(f"x - y = {x - y}")  # Output: x - y = 5
print(f"x * y = {x * y}")  # Output: x * y = 50
```

In the above examples, we used arithmetic expressions inside an F-string to perform calculations and display the results.

### String Formatting

F-strings also support formatting options which allows you to control the way the value is displayed. You can use format specifiers, which start with a colon ':' after the expression. Here is an example:

```python
pi = 3.14159
print(f"Pi is approximately {pi:.2f}.")

#Output: Pi is approximately 3.14.
```

In the above example, we used the formatting option `:.2f` to display the value of `pi` with two decimal places. The `f` stands for floating-point or a float (numbers with decimal point) and the `.2` specifies the precision (number of decimal places).

Formatting options can also be combined with expressions. Here is an example:

```python
value = 123456789
print(f"Formatted value: {value:,}")


#Output: Formatted value: 123,456,789
```

In the above example, we used the formatting option `,` to add comma separators to the value of `value`.

These are just a few methods of using the F-string.

### Resources

For more information on F-strings, you can refer to the official Python documentation:

* [Formatted string literals](https://docs.python.org/3/reference/lexical_analysis.html#f-strings) (Python 3.9 documentation)
    
* [Python 3's f-Strings: An Improved String Formatting Syntax](https://realpython.com/python-f-strings/) (Real Python)
    

F-strings are a powerful feature in Python that can greatly simplify string formatting and make code more readable. With the examples and resources provided, you should be able to start using F-strings in your own Python code.

Thank you for reading! I hope you found this article helpful and encouraging. If you did, kindly like and share it with your friends and colleagues.

I would love to connect with you on [**Twitter**](https://twitter.com/EbubeKamalu) | [**LinkedIn**](https://www.linkedin.com/in/uwaomakamalu) | [**Github**](https://github.com/Ekams26).