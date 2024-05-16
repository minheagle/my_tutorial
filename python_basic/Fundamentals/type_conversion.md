<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Python Type Conversion

**Summary**: in this tutorial, you’ll learn about type conversion in Python and some useful type conversion functions.

#### 1 - Introduction to type conversion in Python

<p>To get input from users, you use the <code>input()</code> function. For example:</p>

```python
    value = input('Enter a value:')
    print(value)
```

<p>When you execute this code, it’ll prompt you for input on the Terminal:</p>

```python
    Enter a value:
```

<p>If you enter a value, for example, a <code>number</code>, the program will display that value back:</p>

```python
    Enter a value:100
    100
```

<p>However, the <code>input()</code> function returns a <code>string</code>, not an <code>integer</code>.</p>

<p>The following example prompts you to enter two input values: net price and tax rate. After that, it calculates the tax and displays the result on the screen:</p>

```python
    price = input('Enter the price ($):')
    tax = input('Enter the tax rate (%):')

    tax_amount = price * tax / 100

    print(f'The tax amount price is ${tax_amount}')
```

<p>When you execute the program and enter some numbers:</p>

```python
    Enter the price ($):100
    Enter the tax rate (%):10
```

<p>… you’ll get the following error:</p>

```python
    Traceback (most recent call last):
    File "main.py", line 4, in <module>
        tax_amount = price * tax / 100
    TypeError: can't multiply sequence by non-int of type 'str'
```

<p>Since the input values are strings, you cannot apply the multiply operator.</p>

<p>To solve this issue, you need to convert the strings to numbers before performing calculations.</p>

<p>To convert a string to a number, you use the <code>int()</code> function. More precisely, the <code>int()</code> function converts a string to an integer.</p>

<p>The following example uses the <code>int()</code> function to convert the input strings to numbers:</p>

```python
    price = input('Enter the price ($):')
    tax = input('Enter the tax rate (%):')

    tax_amount = int(price) * int(tax) / 100
    print(f'The tax amount is ${tax_amount}')
```

<p>If you run the program, and enter some values, you’ll see that it works correctly:</p>

```python
    Enter the price ($):
    100
    Enter the tax rate (%):
    10
    The tax amount is $10.0
```

#### 2 - Other type conversion functions

<p>Besides the <code>int(str)</code> functions, Python supports other type conversion functions. The following shows the most important ones for now:</p>

- <code>float(str)</code> – convert a string to a <code>floating-point number</code>.

- <code>bool(val)</code> – convert a value to a boolean value, either <code>True</code> or <code>False</code>.

- <code>str(val)</code> – return the string representation of a value.

#### 3 - Getting the type of a value

<p>To get the type of value, you use the <code>type(value)</code> function. For example:</p>

```python
    >>> type(100)
    <class 'int'>
    >>> type(2.0)
    <class 'float'>
    >>> type('Hello')
    <class 'str'>
    >>> type(True)
    <class 'bool'>
```

<p>As you can see clearly from the output:</p>

- The number <code>100</code> has the type of <code>int</code>.

- The number <code>2.0</code> has the type of <code>float</code>.

- The string <code>'Hello'</code> has the type of <code>str</code>.

- And the <code>True</code> value has the type of <code>bool</code>.

<p>In front of each type, you see the <code>class</code> keyword. It isn’t important for now. And you’ll learn more about the <code>class</code> later.</p>

#### 4 - Summary

- Use the <code>input()</code> function to get an input string from users.

- Use type conversion functions such as <code>int()</code>, <code>float()</code>, <code>bool()</code>, and <code>str(value)</code> to convert a value from one type to another.

- Use the <code>type()</code> function to get the type of a value.

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="./comments.md"><= Comments</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="../Operators/comparison_operators.md">Comparison operators =></a>
    </div>
</div>
