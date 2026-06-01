# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a = int(input())

if a % 2 == 0:
    print("EVEN")
else:
    print("ODD")
```
## Output
<img width="915" height="228" alt="image" src="https://github.com/user-attachments/assets/418eff70-53f7-4453-9956-741f53741042" />
<img width="916" height="241" alt="image" src="https://github.com/user-attachments/assets/1ef571f9-f313-4973-aaaf-423ecbcf574c" />


## Result
Hence the Python program to check whether the given number is **even** or **odd** using `if...else` statements has been executed successfully.


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
```
a = (0 == True)
b = (False == False)
c = True + True
d = False + 9

print("a is", a)
print("b is", b)
print("c:", c)
print("d:", d)
```
## Output
<img width="919" height="291" alt="image" src="https://github.com/user-attachments/assets/e4eb0cc3-d687-4bab-95c6-c928ecd730bd" />

## Result
Hence the Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False` has been executed successfully.

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```
## Output
<img width="914" height="223" alt="image" src="https://github.com/user-attachments/assets/99557944-c0e3-4052-a955-089f2e521060" />

## Result
Hence the Python program that prints the characters `'T'` and `'a'` using character literals has been executed successfully.

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input())
b = int(input())

x = complex(a, b)

print(x)
print(x.real)
print(x.imag)
```
## Output
<img width="912" height="329" alt="image" src="https://github.com/user-attachments/assets/9c967ff6-c148-4a3d-be2e-f274d2e4b082" />

## Result
Hence the Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts has been executed successfully.
