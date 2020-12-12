# Chapter 1

Without running the code snippets below, I'd like you to write down the expected output. For example:

```python
greeting = 'Hello Grayson!'
print(greeting)

# Answer: Hello Grayson!
```

* Given you call the `sum` function, what would it output?
```python
def sum():
    return 5 + 25

print(sum())

# Answer: ______
```

* Given a function named `greeting`, when you print `greeting`, what does it output?
```python
def greeting():
    return 'Hello Grayson!'

print(greeting)

# Answer: ______
```

* Given you call `main`, what does the `message` variable output when you `print`
```python
def greeting(x):
    return f'Hello, {x}'

def main():
    first_name = 'Grayson'
    
    message = greeting(first_name)
    
    print(message)

main()

# Answer: ______
```

* This is similar, but take a look at the params... Given you call `main`, what does the `message` variable output when you `print`
```python
def greeting(x, y):
    return f'Hello, {x} {y}'

def main():
    first_name = 'Grayson'
    last_name = 'Hardin'

    message = greeting(first_name, last_name)
    
    print(message)

main()

# Answer: ______
```

* One more parameter assignment. Given you call `main`, what does the `message` variable output when you `print`
```python
def greeting(x, y):
    return f'Hello, {x} {y}'

def main():
    first_name = 'Grayson'
    last_name = 'Hardin'

    message = greeting(last_name, first_name)
    
    print(message)

main()

# Answer: ______
```