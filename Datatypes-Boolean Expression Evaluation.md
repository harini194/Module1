
# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program

print("Boolean Expressions:")
print("True and False =", True and False)
print("True or False =", True or False)
print("not True =", not True)
print("not False =", not False)

print("\nArithmetic Expressions:")
print("True + True =", True + True)
print("True - False =", True - False)
print("False * True =", False * True)
print("True * 10 =", True * 10)
print("False + 5 =", False + 5)

## Output

Boolean Expressions:
True and False = False
True or False = True
not True = False
not False = True

Arithmetic Expressions:
True + True = 2
True - False = 1
False * True = 0
True * 10 = 10
False + 5 = 5

## Result

The program executed successfully and showed that boolean values True and False behave as 1 and 0 respectively in arithmetic operations, while logical operations return boolean results.
