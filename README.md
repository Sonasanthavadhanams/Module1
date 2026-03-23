PYTHON PROGRAMMING MODULE 1


NAME: SONA .S 


REGISTER NUMBER: 212224110049


Ex 01: Conditional Statements in Python: Even or Odd Checker


Aim
To write a Python program to check whether the given number is even or odd using if...else statements.

Algorithm
1.Get an input from the user.

2.Convert the input to an integer and store it in a variable a.

3.Use the modulo operator % to check if a % 2 == 0.

1.If true, print "EVEN".

2.Else, print "ODD".
4.End the program.

Program
```
num = int(input())
if num%2==0:
    print("EVEN")
else:
    print("ODD")
```


Output


<img width="489" height="326" alt="image" src="https://github.com/user-attachments/assets/2edd3c79-b75b-4106-80e0-d025fa26f76c" />

Result


Thus the Python Program for determining whether the given number is odd or even has been executed successfully and the output has been verified.

Ex 2:Datatypes-Boolean Expression Evaluation in Python


Aim


To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

Algorithm


1.Set variable a to the result of the expression 0 == True.

2.Set variable b to the result of the expression False == False.

3.Set variable c to the result of the expression True + True.

4.Set variable d to the result of the expression False + 9.

5.Print the value of a with the label "a is".

6.Print the value of b with the label "b is".

7.Print the value of c with the label "c:".

8.Print the value of d with the label "d:".

Program
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


Output


<img width="514" height="399" alt="image" src="https://github.com/user-attachments/assets/4abfcebb-ead8-43a9-ac77-d97d836ae17e" />

Result
Thus the given Python program has been executed successfully and the output has been verified.



EX 03: Datatypes-Character Literal in Python


Aim


To write a Python program that prints the characters 'T' and 'a' using character literals.

Algorithm


1.Print the character 'T'.

2.Print the character 'a'.

Program
```
print('T')
print('a')
```


Output


<img width="606" height="358" alt="image" src="https://github.com/user-attachments/assets/dd2a9a16-a244-4b1e-81c4-018b81549fab" />



Result


Thus the given Python Program has been exceuted successfully and the output has been verified.



EX 04- Datatypes-Complex Number Creation in Python


Aim


To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

Algorithm


1.Read an integer input from the user and assign it to the variable a (real part).

2.Read another integer input from the user and assign it to the variable b (imaginary part).

3.Create a complex number x using the complex(a, b) function.

4.Print the complex number x.

5.Print the real part of x using x.real.

6.Print the imaginary part of x using x.imag.

Program
```
a = int(input())
b = int(input())

x = complex(a, b)

print(x)
print(x.real)
print(x.imag)
```


Output


<img width="307" height="231" alt="image" src="https://github.com/user-attachments/assets/5320bd50-530f-4dde-a15f-2d343e0e603b" />

Result


Therefore the given Python Program has been executed succeefully and the output has been verified.

EX 05-Datatypes-Read and Print a String in Python


Aim


To write a Python program to read a string from the user and then print it.

Algorithm


1.Assign a variable named men_stepped_on_the_moon.

2.Use input() to read a string from the user and store it in the variable.

3.Print the value stored in the variable.

Program
```
men_stepped_on_the_moon = input()
print(men_stepped_on_the_moon)
```
Output
<img width="395" height="226" alt="image" src="https://github.com/user-attachments/assets/12987e60-9ebb-444d-a9bb-4f7bba072c50" />

Result


Therfore the given Python program has been executed successfully and the output has been verified.
