1. Open your terminal and run:
    pip install lark

2. Open VSCode or a Python IDE (anything that allows you to run Python code).

3. Write the following code:
    from lark import Lark
    with open(python.lark, "r", encoding="utf-8") as pylark :
        grammar = pylark.read()
    parser = Lark(grammar)

4. To generate AST, type:
    code = "print('you python code')"
    ast = parser.parse(code)
    print(ast.pretty())
   
