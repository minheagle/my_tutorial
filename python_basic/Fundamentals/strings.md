<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Python Strings

**Summary**: in this tutorial, you’ll learn about Python string and its basic operations.

#### 1 - Introduction to Python string

<p>A string is a series of characters. In Python, anything inside quotes is a string. And you can use either single or double quotes. For example:</p>

```python
    message = 'This is a string in Python'
    message = "This is also a string"
```

<p>If a string contains a single quote, you should place it in double-quotes like this:</p>

```python
    message = "It's a string"
```

<p>And when a string contains double quotes, you can use the single quotes:</p>

```python
    message = '"Beautiful is better than ugly.". Said Tim Peters'
```

<p>To escape the quotes, you use the backslash <code>(\)</code>. For example:</p>

```python
    message = 'It\'s also a valid string'
```

<p>The Python interpreter will treat the backslash character (\) special. If you don’t want it to do so, you can use raw strings by adding the letter r before the first quote. For example:</p>

```python
    message = r'C:\python\bin'
```

<p>Creating multiline strings</p>

<p>To span a string multiple lines, you use triple-quotes “””…””” or ”’…”’. For example:</p>

```python
    help_message = '''
    Usage: mysql command
        -h hostname
        -d database name
        -u username
        -p password
    '''

    print(help_message)
```

<p>It’ll output the following if you execute the program:</p>

```python
    Usage: mysql command
        -h hostname
        -d database name
        -u username
        -p password
```

#### 2 - Using variables in Python strings with the f-strings

<p>Sometimes, you want to use the values of <code>variables</code> in a string.</p>

<p>For example, you may want to use the value of the <code>name</code> variable inside the <code>message</code> string variable:</p>

```python
    name = 'John'
    message = 'Hi'
```

<p>To do it, you place the letter <code>f</code> before the opening quotation mark and put the brace around the variable name:</p>

```python
    name = 'John'
    message = f'Hi {name}'
    print(message)
```

<p>Python will replace the <code>{name}</code> by the value of the <code>name</code> variable. The code will show the following on the screen:</p>

```python
    Hi John
```

<p>The <code>message</code> is a format string, or f-string in short. Python introduced the f-string in version 3.6.</p>

#### 3 - Concatenating Python strings

<p>When you place the string literals next to each other, Python automatically <code>concatenates</code> them into one string. For example:</p>

```python
    greeting = 'Good ' 'Morning!'
    print(greeting)
```

<p>Output:</p>

```python
    Good Morning!
```

<p>To <code>concatenate two string variables</code>, you use the operator <code>+</code>:</p>

```python
    greeting = 'Good '
    time = 'Afternoon'

    greeting = greeting + time + '!'
    print(greeting)
```

<p>Output:</p>

```python
    Good Afternoon!
```

#### 4 - Accessing string elements

<p>Since a string is a <code>sequence</code>  of characters, you can access its elements using an index. The first character in the string has an index of zero.</p>

<p>The following example shows how to access elements using an index:</p>

```python
    str = "Python String"
    print(str[0]) # P
    print(str[1]) # y
```

<p>How it works:</p>

- First, create a variable that holds a string <code>"Python String"</code>.

- Then, access the first and second characters of the string by using the square brackets <code>[]</code> and indexes.

<p>If you use a negative index, Python returns the character starting from the end of the string. For example:</p>

```python
    str = "Python String"
    print(str[-1])  # g
    print(str[-2])  # n
```

<p>The following illustrates the indexes of the string <code>"Python String"</code>:</p>

```python
    +---+---+---+---+---+---+---+---+---+---+---+---+---+
    | P | y | t | h | o | n |   | S | t | r | i | n | g |
    +---+---+---+---+---+---+---+---+---+---+---+---+---+
    0   1   2   3   4   5   6   7   8   9   10  11  12
    -13  -12  -11  -10 -9  -8  -7  -6  -5  -4  -3  -2  -1
```

#### 5 - Getting the length of a string

<p>To get the length of a string, you use the <code>len()</code> function. For example:</p>

```python
    str = "Python String"
    str_len = len(str)
    print(str_len)
```

<p>Output:</p>

```python
    13
```

#### 6 - Slicing strings

<p><code>Slicing</code> allows you to get a substring from a string. For example:</p>

```python
    str = "Python String"
    print(str[0:2])
```

<p>Output:</p>

```python
    Py
```

<p>The <code>str[0:2]</code> returns a substring that includes the character from the index 0 (included) to 2 (excluded).</p>

<p>The syntax for slicing is as follows:</p>

```python
    string[start:end]
```

<p>The substring always includes the character at the <code>start</code> and excludes the string at the <code>end</code>.</p>

<p>The <code>start</code> and <code>end</code> are optional. If you omit the <code>start</code>, it defaults to zero. If you omit the <code>end</code>, it defaults to the string’s length.</p>

#### 7 - Python strings are immutable

<p>Python strings are <code>immutable</code>. It means that you cannot change the string. For example, you’ll get an error if you update one or more characters in a string:</p>

```python
    str = "Python String"
    str[0] = 'J'
```

<p>Error:</p>

```python
    Traceback (most recent call last):
    File "app.py", line 2, in <module>
        str[0] = 'J'
    TypeError: 'str' object does not support item assignment</module>
```

<p>When want to modify a string, you need to create a new one from the existing string. For example:</p>

```python
    str = "Python String"
    new_str = 'J' + str[1:]
    print(new_str)
```

<p>Output:</p>

```python
    Jython String
```

#### 8 - Summary

- In Python, a string is a series of characters. Also, Python strings are immutable.

- Use quotes, either single quotes or double quotes to create string literals.

- Use the backslash character <code>\\</code> to escape quotes in strings.

- Use raw strings <code>r'...'</code> to escape the backslash character.

- Use f-strings to insert substitute variables in literal strings.

- Place literal strings next to each other to concatenate them. And use the + operator to concatenate string variables.

- Use the <code>len()</code> function to get the size of a string.

- Use the <code>str[n]</code> to access the character at the position n of the string <code>str</code>.

- Use slicing to extract a substring from a string.

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="./variables.md"><= Variables</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="./numbers.md">Numbers =></a>
    </div>
</div>
