
MODULE 1

Conditional Statements in Python: Even or Odd Checker

##Aim

To write a Python program to check whether the given number is even or odd using if...else statements.

##Algorithm

Get an input from the user.
Convert the input to an integer and store it in a variable a.
Use the modulo operator % to check if a % 2 == 0.
If true, print "EVEN".
Else, print "ODD".
End the program.


##Program

number = int(input("Enter a number: "))

if number % 2 == 0:
    print(f"{number} is Even.")
else:
    print(f"{number} is Odd.")


Output

<img width="1198" height="230" alt="image" src="https://github.com/user-attachments/assets/0d8d7808-08f1-4a83-b8ce-de922aada5e0" />


Result

Thus program has been executed successfully.

Ex 1:Datatypes-Boolean Expression Evaluation in Python

##Aim

To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving True and False.

##Algorithm
Set variable a to the result of the expression 0 == True.
Set variable b to the result of the expression False == False.
Set variable c to the result of the expression True + True.
Set variable d to the result of the expression False + 9.
Print the value of a with the label "a is".
Print the value of b with the label "b is".
Print the value of c with the label "c:".
Print the value of d with the label "d:".


##Program

print(f"True and False: {True and False}")
print(f"True or False: {True or False}")
print(f"not True: {not True}")
print(f"True + True: {True + True}")
print(f"True - False: {True - False}")
print(f"True * 5: {True * 5}")
print(f"False / True: {False / True}")

Output

<img width="1207" height="338" alt="image" src="https://github.com/user-attachments/assets/131be201-eac7-4448-b78b-97dec5a4a8df" />


Result
Thus program has been executed successfully.


Datatypes-Character Literal in Python

##Aim

To write a Python program that prints the characters 'T' and 'a' using character literals.

##Algorithm

Print the character 'T'.
Print the character 'a'.

##Program

print('T')
print('a')


Output
<img width="925" height="166" alt="image" src="https://github.com/user-attachments/assets/67238788-85bc-41c0-8ffa-02abad854551" />


Result
Thus program has been executed successfully.



Datatypes-Complex Number Creation in Python

##Aim

To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

##Algorithm


Read an integer input from the user and assign it to the variable a (real part).
Read another integer input from the user and assign it to the variable b (imaginary part).
Create a complex number x using the complex(a, b) function.
Print the complex number x.
Print the real part of x using x.real.
Print the imaginary part of x using x.imag.

##Program

real_part = int(input("Enter real part: "))
imag_part = int(input("Enter imaginary part: "))

complex_num = complex(real_part, imag_part)

print("Complex number:", complex_num)
print("Real part:", complex_num.real)
print("Imaginary part:", complex_num.imag)


Output

<img width="1238" height="412" alt="image" src="https://github.com/user-attachments/assets/e5902ba3-05b7-4c15-9591-4eaffb7d3057" />

Result

Thus program has been executed successfully.

Datatypes-Read and Print a String in Python
##Aim

To write a Python program to read a string from the user and then print it.

##Algorithm


Assign a variable named men_stepped_on_the_moon.
Use input() to read a string from the user and store it in the variable.
Print the value stored in the variable.

##Program

user_string = input("Enter a string: ")
print(user_string)


Output

<img width="1208" height="462" alt="image" src="https://github.com/user-attachments/assets/fdb46c69-3385-4b9a-81cc-27d8f49a79e8" />

Result
 
 Thus program has been executed successfully.

