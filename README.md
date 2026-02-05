````md
# Writing Your First Python Program (Functions)

````
# 1. Python Program
- A Python program is a set of instructions written to perform a task.
- Python executes code line by line.
- Indentation is mandatory.

# 2. Basic Python Program Using Function
```python
print("Hello, World!")
````

## 3. Function

* A function is a block of reusable code.
* It performs a specific task.
* It runs only when called.

## 4. Defining a Function

* Use the keyword `def`.
* End the definition with `:`.

```python
def greet():
    print("Hello, World!")
```

## 5. Calling a Function

* Use function name followed by parentheses `()`.

```python
greet()
```

## 6. Function with Parameters

* Parameters pass values to a function.

```python
def greet(name):
    print("Hello", name)

greet("Nayana")
```

## 7. Function with Return Value

* `return` sends a value back.

```python
def add(a, b):
    return a + b

result = add(3, 5)
print(result)
```

## 8. First Complete Program Using Function

```python
def main():
    print("My first Python program")

main()
```

## 9. Important Rules

* Indentation is compulsory.
* Function names should be lowercase.
* Use underscore for multiple words.

## 10. Keywords to Remember

* def
* return
* print
