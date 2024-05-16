<h1 style="color:red">MinhEagle Tutorial !</h1>

<div style="width:100%;display:flex;justify-content:flex-start;align-items:center;gap:24px;padding-bottom:24px">
    <div>
        <a href="../README.md">Home page</a>
    </div>
    <div>
        <a href="../overview.md">Python Basic</a>
    </div>
</div>

### Python Syntax

**Summary**: in this tutorial, you’ll learn about the basic Python syntax so that you can get started with the Python language quickly.

#### 1 - Whitespace and indentation

<p>If you’ve been working in other programming languages such as Java, C#, or C/C++, you know that these languages use semicolons (;) to separate the statements.</p>

<p>However, Python uses whitespace and indentation to construct the code structure.</p>

<p>The following shows a snippet of Python code:</p>

```python
    # define main function to print out something
    def main():
        i = 1
        max = 10
        while (i < max):
            print(i)
            i = i + 1

    # call function main
    main()
```

<p>The meaning of the code isn’t important to you now. Please pay attention to the code structure instead.</p>

<p>At the end of each line, you don’t see any semicolon to terminate the statement. And the code uses indentation to format the code.</p>

<p>By using indentation and whitespace to organize the code, Python code gains the following advantages:</p>

- First, you’ll never miss the beginning or ending code of a block like in other programming languages such as Java or C#.

- Second, the coding style is essentially uniform. If you have to maintain another developer’s code, that code looks the same as yours.

- Third, the code is more readable and clear in comparison with other programming languages.

#### 2 - Comments

<p>The comments are as important as the code because they describe why a piece of code was written.</p>

<p>When the Python interpreter executes the code, it ignores the comments.</p>

<p>In Python, a single-line comment begins with a hash (#) symbol followed by the comment. For example:</p>

```python
    # This is a single line comment in Python
```

<p>And Python also supports other kinds of <code>comments</code>.</p>

#### 3 - Continuation of statements

<p>Python uses a newline character to separate statements. It places each statement on one line.</p>

<p>However, a long statement can span multiple lines by using the backslash (\) character.</p>

<p>The following example illustrates how to use the backslash (\) character to continue a statement in the second line:</p>

```python
    if (a == True) and (b == False) and \
        (c == True):
        print("Continuation of statements")
```

#### 4 - Identifiers

<p>Identifiers are names that identify <code>variables</code>, <code>functions</code>, <code>modules</code>, <code>classes</code>, and other objects in Python.</p>

<p>The name of an identifier needs to begin with a letter or underscore (_). The following characters can be alphanumeric or underscore.</p>

<p>Python identifiers are case-sensitive. For example, the <code>counter</code> and <code>Counter</code> are different identifiers.</p>

<p>In addition, you cannot use Python keywords for naming identifiers.</p>

#### 5 - Keywords

<p>Some words have special meanings in Python. They are called keywords.</p>

<p>The following shows the list of keywords in Python:</p>

```python
    False      class      finally    is         return
    None       continue   for        lambda     try
    True       def        from       nonlocal   while
    and        del        global     not        with
    as         elif       if         or         yield
    assert     else       import     pass
    break      except     in         raise
```

<p>Python is a growing and evolving language. So its keywords will keep increasing and changing.</p>

<p>Python provides a special module for listing its keywords called <code>keyword</code>.</p>

<p>To find the current keyword list, you use the following code:</p>

```python
    import keyword

    print(keyword.kwlist)
```

#### 6 - String literals

<p>Python uses single quotes ('), double quotes ("), triple single quotes (''') and triple-double quotes (""") to denote a string literal.</p>

<p>The string literal need to be surrounded with the same type of quotes. For example, if you use a single quote to start a string literal, you need to use the same single quote to end it.</p>

<p>The following shows some examples of string literals:</p>

```python
    s = 'This is a string'
    print(s)
    s = "Another string using double quotes"
    print(s)
    s = ''' string can span
            multiple line '''
    print(s)
```

#### 7 - Summary

- A Python statement ends with a newline character.

- Python uses spaces and indentation to organize its code structure.

- Identifiers are names that identify variables, functions, modules, classes, etc. in Python.

- Comments describe why the code works. They are ignored by the Python interpreter.

- Use the single quote, double-quotes, triple-quotes, or triple double-quotes to denote

<div style="width:100%;display:flex;justify-content:space-between;align-items:center;gap:24px">
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-end;align-items:center;padding-right:16px">
        <a href="../overview.md"><= Python Basic</a>
    </div>
    <div style="width:50%;height:48px;border-style:solid;border-width:2px;border-radius:12px;display:flex;justify-content:flex-start;align-items:center;padding-left:16px">
        <a href="./variables.md">Variables =></a>
    </div>
</div>
