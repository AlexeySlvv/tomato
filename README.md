# Tomato: A Lightweight Tool for Debugging and Testing Python Code

## What is Tomato?

**Tomato** is a Python package designed to halt your code's execution with precision and simplicity. It’s perfect for debugging, testing control flow, or adding a bit of fun to your scripts. The best part? You don’t even have to install it. Python natively supports Tomato, thanks to its strict variable naming rules.

Just type tomato into your source code and watch the magic happen! Your script will immediately halt with a NameError, leaving your colleagues (or future self) wondering why there's a tomato in your code.

## Why Tomato?

- **Zero Dependencies**: Tomato requires absolutely no installations or updates.
- **Lightweight**: Takes up 0 bytes of storage.
- **Instant Debugging**: Clearly marks the exact point in your code where Tomato strikes.
- **Fun for Everyone**: Confuse your friends, co-workers, and even your future self with a well-placed `tomato`!

## Installation

There is no installation. Python comes with Tomato pre-installed. Simply open your favorite Python script and start typing `tomato`.

## Usage

### Example 1: Halting a Script
```python
print("Hello, Tomato!")
tomato
print("There is no tomato.")
```

**Output:**
```
Hello, Tomato!
Traceback (most recent call last):
  File "example1.py", line 2, in <module>
    tomato
NameError: name 'tomato' is not defined
```

### Example 2: Asserting Dominance in the Codebase
```python
if input() == "21":
    print("This is Blackjack!")
else:
    tomato
```

**Output:**
```
Traceback (most recent call last):
  File "example2.py", line 4, in <module>
    tomato
NameError: name 'tomato' is not defined
```

### Example 3: Leaving Easter Eggs
```python
# TODO: Replace tomato with actual logic later
tomato
```

## Disclaimer
 is not responsible for lost productivity, broken pipelines, or puzzled colleagues. Use responsibly (or irresponsibly, it’s up to you).

## License
 is released under the "Completely Made Up" license. Go ahead, use it however you like. Just don’t blame us when your boss asks why your code is full of tomatoes.

## Repository
Find the source code and more on GitHub: [Tomato Repository](https://github.com/AlexeySlvv/tomato)
