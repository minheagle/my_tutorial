<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Numbers

**Summary**: in this tutorial, you’ll learn about Python numbers and how to use them in programs.

Python supports integers, floats, and complex numbers. This tutorial discusses only integers and floats.

#### 1 - Python Integers

<p>The <code>integers</code> are numbers such as -1, 0, 1, 2, and 3, .. and they have type <code>int</code>.</p>

<p>You can use Math operators like +, -, \*, and / to form expressions that include integers. For example:</p>

```python
    >>> 20 + 10
    30
    >>> 20 - 10
    10
    >>> 20 * 10
    200
    >>> 20 / 10
    2.0
```

<p>To calculate exponents, you use two multiplication symbols <code>(**)</code>. For example:</p>

```python
    >>> 3**3
    27
```

<p>To modify the order of operations, you use the parentheses <code>()</code>. For example:</p>

```python
    >>> 20 / (10 + 10)
    1.0
```

#### 2 - Floats

<p>Any number with a decimal point is a <code>floating-point number</code>. The term float means that the decimal point can appear at any position in a number.</p>

<p>In general, you can use floats like integers. For example:</p>

```python
    >>> 0.5 + 0.5
    1.0
    >>> 0.5 - 0.5
    0.0
    >>> 0.5 / 0.5
    1.0
    >>> 0.5 * 0.5
    0.25
```

<p>The division of two integers always returns a float:</p>

```python
    >>> 20 / 10
    2.0
```

<p>If you mix an integer and a float in any arithmetic operation, the result is a float:</p>

```python
    >>> 1 + 2.0
    3.0
```

<p>Due to the internal representation of floats, Python will try to represent the result as precisely as possible. However, you may get the result that you would not expect. For example:</p>

```python
    >>> 0.1 + 0.2
    0.30000000000000004
```

<p>Just keep this in mind when you perform calculations with floats. And you’ll learn how to handle situations like this in <code>later tutorials</code>.</p>

#### 3 - Underscores in numbers

<p>When a number is large, it’ll become difficult to read. For example:</p>

```python
    count = 10000000000
```

<p>To make the long numbers more readable, you can group digits using underscores, like this:</p>

```python
    count = 10_000_000_000
```

<p>When storing these values, Python just ignores the underscores. It does so when displaying the numbers with underscores on the screen:</p>

```python
    count = 10_000_000_000
    print(count)
```

<p>Output:</p>

```python
    10000000000
```

<p>The underscores also work for both integers and floats.</p>

> ---
>
> Note that the underscores in numbers have been available since Python 3.6
>
> ---

#### 4 - Summary

- Python supports common numeric types including integers, floats, and complex numbers.

- Use the underscores to group numbers for the large numbers.

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="./strings.md"><= Strings</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="./booleans.md">Booleans =></a>
    </div>
</div>
