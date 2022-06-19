# 0x00-python-hello_world
######
## Learning objectives
######
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
- Why Python programming is awesome
- Who created Python
- Who is Guido van Rossum
- Where does the name ‘Python’ come from
- What is the Zen of Python
- How to use the Python interpreter
- How to print text and variables using print
- How to use strings
- What are indexing and slicing in Python
- What is the official Python coding style and how to check your code with pycodestyle

## Tasks
0. Run python file
   - Write a Shell script that runs a Python script.
   - The Python file name will be saved in the environment variable $PYFILE
1. Run inline
   - Write a Shell script that runs Python code.
   - The Python code will be saved in the environment variable $PYCODE
2. Hello, print
   - Write a Python script that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.
3. Print integer
   - Complete a source code
4. Print float
   - Complete a source code
5. Print string
   - Complete a source code
6. Play with strings
   - Complete a source code
7. Copy - Cut - Paste
   - Complete a source code
8. Create a new sentence
   - Complete a source code
9. Easter egg
   - Write a Python script that prints “The Zen of Python”, by TimPeters, followed by a new line.
10. Linked list cycle
11. Hello, write
   - Write a Python script that prints exactly and that piece of art is useful - Dora Korpar, 2015-10-19, followed by a new line.
12. Compile
   - Write a script that compiles a Python script file.
   - The Python file name will be stored in the environment variable $PYFILE
   - The output filename has to be $PYFILEc (ex: export PYFILE=my_main.py => output filename: my_main.pyc)
13. ByteCode->Python#1
  - Write the Python function def magic_calculation(a, b): that does exactly the same as the following Python bytecode:
   ```
    3           0 LOAD_CONST               1 (98)
              3 LOAD_FAST                0 (a)
              6 LOAD_FAST                1 (b)
              9 BINARY_POWER
             10 BINARY_ADD
             11 RETURN_VALUE
   
