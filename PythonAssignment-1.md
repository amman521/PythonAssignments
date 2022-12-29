## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Answer-> Python Programming Language that is designed to be used in a wide variety of domains.
Python Programming Language that does not depend on any particular type of Computer Machine to write Codes.

Q2. Why is Python called a dynamically typed language?

Answer-> No need to use data type before variable name to define a variable.

Q3. List some pros and cons of Python programming language?

Answer-> Pros are Simple,High level language,Huge Library,Open Source.
        Cons are Runtime errors,Slower,Slower than compiled Language.

Q4. In what all domains can we use Python?

Answer-> By using Python we can developed many things like->
1.Web Application(Django)
2.Data Science
3.Machine Learning
4.Artificial Intelligence etc etc.

Q5. What are variable and how can we declare them?

Answer-> Varibales are containers for storing data values.
Ex-> int_var = 10
    float_car = 10.5
    str_var = "iNeouron"
    list_var = [10,20,30,40,50]
    dict_var = { "name" : "xyz", "age" :36}
etc etc.

Q6. How can we take an input from the user in Python?

Answer-> We can use input() function for that.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Answer->Default data type returns a String.

Q8. What is type casting?

Answer-> The Conversion of one data type into the other data type is known as type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Answer-> We can take multiple inputs in one single line
x, y = input("Enter First Name: "), input("Enter Last Name: ")
print("First Name is: ", x)
print("Second Name is: ", y)

or

x,y=input("Enter three values: ").spilt(",")
print("First Name is: ", x)
print("Second Name is: ", y)

Q10. What are keywords?

Answer-> Reserved words having some specific meaning.

Q11. Can we use keywords as a variable? Support your answer with reason.

Answer-> No,keywords are reserved for the programming language and can’t be used for anything else.

Q12. What is indentation? What's the use of indentaion in Python?

Answer-> Identation refers to the spaces and tabs used at the begining of a code line.
Python uses identation to indicate a block of code.

Q13. How can we throw some output in Python?

Answer-> Python print() function prints the output.

Q14. What are operators in Python?

Answer-> Operators which perform some operation on operand.
There are many operators in Python like Arithmetic Operator,Relational Operator,Assignment Operator,Logical Operator,Bitwise Operator.

Q15. What is difference between / and // operators?

Answer-> / operators is use for Float Division and // operator is use for Integer operator.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Answer-> str_data = 'iNeuron'*4
        print(str_data)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Answer-> int_num = int(input("Enter your number"))
if int_num%2==0:
    print("Number is even number",int_num)
else:
    print("Number is odd number",int_num)

Q18. What are boolean operator?

Answer-> boolean operator referred as logical operator and its returns true or false value.

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Answer-> 1 or 0 = 1
0 and 0 = 0
true and False and True = False
1 and 0 or 0 = 1

Q20. What are conditional statements in Python?

Answer-> conditional statement used to handle conditions in program.

Q21. What is use of 'if', 'elif' and 'else' keywords?

Answer-> All the three keywords are decision making first it check 'if' part if first statement is correct then it will execute.
if the 'if' statement not satisfy then else part will execute.
If we have many conditions to check where we use elif.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Answer-> int_age=int(input("Enter your age"))
if int_age>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer->
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for i in numbers:
    if i % 2 == 0:
        sum+=i
        print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Answer->

int_num1=int(input("Enter number 1"))
int_num2=int(input("Enter number 2"))
int_num3=int(input("Enter number 3"))

if int_num1>int_num2 and int_num1>int_num3:
    print(int_num1,"int num 1 is greater")
elif int_num2>int_num1 and int_num2>int_num3:
    print(int_num2,"int_num2 is greater")
else:
    print(int_num3,"int_num3 is greater")


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Answer->
numbers = [12, 75, 150, 180, 145, 525, 50]
list = []
for num in numbers:
  if num > 150:
    if num > 500:
      break
  elif num%5==0:
    lst.append(num)

print(list)