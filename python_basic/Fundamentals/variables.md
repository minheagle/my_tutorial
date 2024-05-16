<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Python Variables

**Summary**: in this tutorial, you’ll learn about Python variables and how to use them effectively.

#### 1 - What is a variable in Python

<p>When you develop a program, you need to manage values, a lot of them. To store values, you use variables.</p>

<p>In Python, a variable is a label that you can assign a value to it. And a variable is always associated with a value. For example:</p>

```python
    message = 'Hello, World!'
    print(message)

    message = 'Good Bye!'
    print(message)
```

<p>Output:</p>

```python
    Hello, World!
    Good Bye!
```

<p>In this example, <code>message</code> is a variable. It holds the string <code>'Hello, World!'</code>. The <code>print()</code> function shows the message <code>Hello, World!</code> to the screen.</p>

<p>The next line assigns the string <code>'Good Bye!'</code> to the <code>message</code> variable and print its value to the screen.</p>

<p>The variable <code>message</code> can hold various values at different times. And its value can change throughout the program.</p>

#### 2 - Creating variables

<p>To define a variable, you use the following syntax:</p>

```python
    variable_name = value
```

<p>The <code>=</code> is the assignment operator. In this syntax, you assign a value to the <code>variable_name</code>.</p>

<p>The value can be anything like a <code>number</code>, a <code>string</code>, etc., that you assign to the variable.</p>

<p>The following defines a variable named <code>counter</code> and assigns the number 1 to it:</p>

```python
    counter = 1
```

#### 3 - Naming variables

<p>When you name a variable, you need to adhere to some rules. If you don’t, you’ll get an error.</p>

<p>The following are the variable rules that you should keep in mind:</p>

- Variable names can contain only letters, numbers, and underscores <code>(_)</code>. They can start with a letter or an underscore <code>(_)</code>, not with a number.

- Variable names cannot contain spaces. To separate words in variables, you use underscores for example <code>sorted_list</code>.

- Variable names cannot be the same as keywords, reserved words, and built-in functions in Python.

<p>The following guidelines help you define good variable names:</p>

- Variable names should be concise and descriptive. For example, the <code>active_user</code> variable is more descriptive than the <code>au</code>.

- Use underscores <code>(\_)</code> to separate multiple words in the variable names.

- Avoid using the letter <code>1</code> and the uppercase letter <code>0</code> because they look like the number <code>1</code> and <code>0</code>.

#### 4 - Summary

- A variable is a label that you can assign a value to it. The value of a variable can change throughout the program.

- Use the <code>variable_name = value</code> to create a variable.

- The variable names should be as concise and descriptive as possible. Also, they should adhere to Python variable naming rules.

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="./syntax.md"><= Syntax</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="./strings.md">Strings =></a>
    </div>
</div>
