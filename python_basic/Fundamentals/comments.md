<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Python Comments

**Summary**: in this tutorial, you’ll learn how to add comments to your code. And you’ll learn various kinds of Python comments including block comments, inline comments, and documentation string.

#### 1 - Introduction to Python comments

<p>Sometimes, you want to document the code that you write. For example, you may want to note why a piece of code works. To do it, you use the comments.</p>

<p>Typically, you use comments to explain formulas, algorithms, and complex business logic.</p>

<p>When executing a program, the Python interpreter ignores the comments and only interprets the code.</p>

<p>Python provides three kinds of comments including block comment, inline comment, and documentation string.</p>

#### 2 - Python block comments

<p>A block comment explains the code that follows it. Typically, you indent a block comment at the same level as the code block.</p>

<p>To create a block comment, you start with a single hash sign (<code>#</code>) followed by a single space and a text string. For example:</p>

```python
    # increase price by 5%
    price = price * 1.05
```

#### 3 - Python inline comments

<p>When you place a comment on the same line as a statement, you’ll have an inline comment.</p>

<p>Similar to a block comment, an inline comment begins with a single hash sign (<code>#</code>) and is followed by a space and a text string.</p>

<p>The following example illustrates an inline comment:</p>

```python
    salary = salary * 1.02   # increase salary by 2%
```

#### 4 - Python docstrings

<p>A documentation string is a <code>string</code> literal that you put as the first lines in a code block, for example, a <code>function</code>.</p>

<p>Unlike a regular comment, a documentation string can be accessed at run-time using  <code>obj.__doc__</code> attribute where <code>obj</code> is the name of the <code>function</code>.</p>

<p>Typically, you use a documentation string to automatically generate the code documentation.</p>

<p>Documentation strings is called docstrings.</p>

<p>Technically speaking, docstrings are not the comments. They create anonymous variables that reference the strings. Also, they’re not ignored by the Python interpreter.</p>

<p>Python provides two kinds of docstrings: one-line docstrings and multi-line docstrings.</p>

**1) One-line docstrings**

<p>As its name implies, a one-line docstring fits one line. A one-line docstring begins with triple quotes (<code>"""</code>) and also ends with triple quotes (<code>"""</code>). Also, there won’t be any blank line either before or after the one-line docstring.</p>

<p>The following example illustrates a one-line docstring in the <code>quicksort()</code> function:</p>

```python
    def quicksort():
    """ sort the list using quicksort algorithm """
    ...
```

**2) Multi-line docstrings**

<p>Unlike a one-line docstring, a multi-line docstring can span multiple lines. A multi-line docstring also starts with triple quotes (<code>"""</code>) and ends with triple quotes (<code>"""</code>).</p>

<p>The following example shows you how to use multi-line docstrings:</p>

```python
    def increase(salary, percentage, rating):
        """ increase salary base on rating and percentage
        rating 1 - 2 no increase
        rating 3 - 4 increase 5%
        rating 4 - 6 increase 10%
        """
```

#### 5 - Python multiline comments

<p>Python doesn’t support multiline comments.</p>

<p>However, you can use multi-line docstrings as multiline comments. <code>Guido van Rossum</code>, the creator of Python, also recommended this.</p>

<p>It’s a good practice to keep your comment clear, concise, and explanatory. The ultimate goal is to save time and energy for you and other developers who will work on the code later.</p>

#### 6 - Summary

- Use comments to document your code when necessary.

- A block comment and inline comment starts with a hash sign (<code>#</code>).

- Use docstrings for <code>functions</code>, <code>modules</code>, and <code>classes</code>.

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="./constants.md"><= Constants</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="./type_conversion.md">Type conversion =></a>
    </div>
</div>
