# Potato: A Lightweight Tool for Debugging and Testing Python Code

## What is Potato?

**Potato** is a Python package designed to halt your code's execution with precision and simplicity. It’s perfect for debugging, testing control flow, or adding a bit of fun to your scripts. The best part? You don’t even have to install it. Python natively supports Potato, thanks to its strict variable naming rules.

Just type potato into your source code and watch the magic happen! Your script will immediately halt with a NameError, leaving your colleagues (or future self) wondering why there's a potato in your code.

## Why Potato?

- **Zero Dependencies**: Potato requires absolutely no installations or updates.
- **Lightweight**: Takes up 0 bytes of storage.
- **Instant Debugging**: Clearly marks the exact point in your code where Potato strikes.
- **Fun for Everyone**: Confuse your friends, co-workers, and even your future self with a well-placed `potato`!

## Installation

There is no installation. Python comes with Potato pre-installed. Simply open your favorite Python script and start typing `potato`.

## Usage

### Example 1: Halting a Script
```python
print("Hello, world!")
potato
print("This will never run.")
```

**Output:**
```
Hello, world!
Traceback (most recent call last):
  File "example.py", line 2, in <module>
    potato
NameError: name 'potato' is not defined
```

### Example 2: Asserting Dominance in the Codebase
```python
if user_input == "42":
    print("You cracked the ultimate answer!")
else:
    potato
```

**Output:**
```
Traceback (most recent call last):
  File "example.py", line 4, in <module>
    potato
NameError: name 'potato' is not defined
```

### Example 3: Leaving Easter Eggs
```python
# TODO: Replace potato with actual logic later
potato
```

## Disclaimer
Potato is not responsible for lost productivity, broken pipelines, or puzzled colleagues. Use responsibly (or irresponsibly, it’s up to you).

## Contribute
Have ideas to make Potato even better? Sorry, but it’s already perfect.

## License
Potato is released under the "Completely Made Up" license. Go ahead, use it however you like. Just don’t blame us when your boss asks why your code is full of potatoes.

## Repository
Find the source code and more on GitHub: [Potato Repository](https://github.com/andrewruba/potato)
