# **সাধারণ পাইথন প্রোগ্রাম**

```py title="hello.py" linenums="1" hl_lines="2"
def greet():
    name = input("Please enter your name: ") # (1)
    print(f"Hello, {name}!")
```

1.  :simple-python: This takes the user's `name` as input.

```py title="embedded_hello.py" linenums="1" hl_lines="2"
--8<-- "docs_src/sample_script/hello.py"
```