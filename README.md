I don't know what to put here, haha.

## Python in Python!

Created by **ItsDasheer** :D

### This file supports:
- **Conditional blocks**
- **Object-Oriented Programming (OOP)**
- **Variables and functions**
- **And more**

### How to install Lark
- Open your terminal and run:
  * pip install lark

### Usage
```python
from lark import Lark

with open("python.lark", "r") as pylark:
    grammar = pylark.read()

parser = Lark(grammar, parser='lalr')

code = """
print("you code here!")
"""

ast = parser.parse(code)
print(ast.pretty())
```

bye
