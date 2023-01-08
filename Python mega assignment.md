Q1. Why do we call Python as a general purpose and high-level programming language?

Answer-> Python Programming Language that is designed to be used in a wide variety of domains. Python Programming Language that does not depend on any particular type of Computer Machine to write Codes.

Q2. Why is Python called a dynamically typed language?

Answer-> No need to use data type before variable name to define a variable.

Q3. List some pros and cons of Python programming language?

Answer-> Pros are Simple,High level language,Huge Library,Open Source. Cons are Runtime errors,Slower,Slower than compiled Language.

Q4. In what all domains can we use Python?

Answer-> By using Python we can developed many things like-> 1.Web Application(Django) 2.Data Science 3.Machine Learning 4.Artificial Intelligence etc etc.

Q5. What are variable and how can we declare them?

Answer-> Varibales are containers for storing data values. Ex-> int_var = 10 float_car = 10.5 str_var = "iNeouron" list_var = [10,20,30,40,50] dict_var = { "name" : "xyz", "age" :36} etc etc.

Q6. How can we take an input from the user in Python?

Answer-> We can use input() function for that.

Q7. What is the default datatype of the value that has been taken as an input using input() function?

Answer->Default data type returns a String.

Q8. What is type casting?

Answer-> The Conversion of one data type into the other data type is known as type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Answer-> We can take multiple inputs in one single line x, y = input("Enter First Name: "), input("Enter Last Name: ") print("First Name is: ", x) print("Second Name is: ", y)

or

x,y=input("Enter three values: ").spilt(",") print("First Name is: ", x) print("Second Name is: ", y)

Q10. What are keywords?

Answer-> Reserved words having some specific meaning.

Q11. Can we use keywords as a variable? Support your answer with reason.

Answer-> No,keywords are reserved for the programming language and can’t be used for anything else.

Q12. What is indentation? What's the use of indentaion in Python?

Answer-> Identation refers to the spaces and tabs used at the begining of a code line. Python uses identation to indicate a block of code.

Q13. How can we throw some output in Python?

Answer-> Python print() function prints the output.

Q14. What are operators in Python?

Answer-> Operators which perform some operation on operand. There are many operators in Python like Arithmetic Operator,Relational Operator,Assignment Operator,Logical Operator,Bitwise Operator.

Q15. What is difference between / and // operators?

Answer-> / operators is use for Float Division and // operator is use for Integer operator.

Q16. Write a code that gives following as an output.

iNeuroniNeuroniNeuroniNeuron
Answer-> str_data = 'iNeuron'*4 print(str_data)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Answer-> int_num = int(input("Enter your number")) if int_num%2==0: print("Number is even number",int_num) else: print("Number is odd number",int_num)

Q18. What are boolean operator?

Answer-> boolean operator referred as logical operator and its returns true or false value.

Q19. What will the output of the following?

1 or 0

0 and 0

True and False and True

1 or 0 or 0
Answer-> 1 or 0 = 1 0 and 0 = 0 true and False and True = False 1 and 0 or 0 = 1

Q20. What are conditional statements in Python?

Answer-> conditional statement used to handle conditions in program.

Q21. What is use of 'if', 'elif' and 'else' keywords?

Answer-> All the three keywords are decision making first it check 'if' part if first statement is correct then it will execute. if the 'if' statement not satisfy then else part will execute. If we have many conditions to check where we use elif.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Answer-> int_age=int(input("Enter your age")) if int_age>=18: print("I can vote") else: print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.

numbers = [12, 75, 150, 180, 145, 525, 50]
Answer-> numbers = [12, 75, 150, 180, 145, 525, 50] sum = 0 for i in numbers: if i % 2 == 0: sum+=i print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Answer->

int_num1=int(input("Enter number 1")) int_num2=int(input("Enter number 2")) int_num3=int(input("Enter number 3"))

if int_num1>int_num2 and int_num1>int_num3: print(int_num1,"int num 1 is greater") elif int_num2>int_num1 and int_num2>int_num3: print(int_num2,"int_num2 is greater") else: print(int_num3,"int_num3 is greater")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

The number must be divisible by five

If the number is greater than 150, then skip it and move to the next number

If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
Answer-> numbers = [12, 75, 150, 180, 145, 525, 50] list = [] for num in numbers: if num > 150: if num > 500: break elif num%5==0: lst.append(num)

print(list)

Q26. What is a string? How can we declare string in Python?
Answer->    Strings are surrounded by either single quotation marks or double quotation marks.
str_var = 'iNeuron' #this way we can assign or declare a string.

Q27. How can we access the string using its index?
Answer->   String index can be accessed by using string name with square brackets.

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"

Answer->  print(string[9:16]) 

Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"

Answer -> print(string1[15:8:-1])

Q30. Resverse the string given in the above question.
string2 = "Big Data iNeuron"
print(string2[::-1])

Q31. How can you delete entire string at once?
Answer -> We can delete entire string at once using del function.

Q32. What is escape sequence?
Answer->  Escape sequence allow us to include special character in strings.

Q33. How can you print the below string?

'iNeuron's Big Data Course'

Answer-> print('iNeuron's Big Data Course')

Q34. What is a list in Python?
Answer-> A list is a collection of elements separated by commas and enclosed within square brackets.

Q35. How can you create a list in Python?
Answer-> list1 = [20,30,40,50,"iNeuron"]
               
Q36. How can we access the elements in a list?
Answer- > We can access the element by their indexing.

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]

print(lst[4][2])
                          
Q38. Take a list as an input from the user and find the length of the list.
Answer -> list1 = input("Enter your list").split(" ")
print(len(list1))
               
Q39. Add the word "Big" in the 3rd index of the given list.

lst1 = ["Welcome", "to", "Data", "course"]
lst1.insert(2, "Big")
print(lst1)
               
Q40. What is a tuple? How is it different from list?
Answer-> Tuple is defined within parenthese where items are seprated by commas.The difference between tuples and list is that tuples are immutable.

Q41. How can you create a tuple in Python?    
Answer-> tup1 = (20,30,50,40)
               
Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.              
Answer-> No the reason is tuples are immutable so first we have typecast list then we can append.
tup1 = ()
tup1 = list(tup1)
tup1.append("Amman")
tup1 = tuple(tup1)
print(tup1)

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
Answer-> tup2 = ("Amman")
tup3 = ("Khan")
print(tup2+tup3)              
               
Q44. Take a tuple as an input and print the count of elements in it.
Answer-> tup4 = input("Enter").split(" ")
tup4 = tuple(tup4)
print(len(tup4))

Q45. What are sets in Python?
Answer-> Set is an unordered collection of elements where duplicates are not allowed.              
               
Q46. How can you create a set?              
Answer-> We can create a set separated by comma inside curly braces 
set1= {10,20,30,40,50}              
               
Q47. Create a set and add "iNeuron" in your set.              
Answer-> set1 = {"iNeuron"}
print(set1)               

Q48. Try to add multiple values using add() function.               
Answer-> thisset={" "}
thisset.add("Amman")
thisset.add("Khan")
print(thisset)               
               
Q49. How is update() different from add()?               
Answer-> The update() method find union and update in one set,but in add() we just add an element to set.             
               
Q50. What is clear() in sets?
Answer-> clear() method makes a set empty.
               
Q51. What is frozen set?               
Answer-> the frozenset type is immutable, meaning it can't be changed.   
               
Q52. How is frozen set different from set?
Answer-> the frozenset type is immutable, meaning it can't be changed.But set is mutable it can be changed.

Q53. What is union() in sets? Explain via code.
Answer-> The union() method returns a set that contains all items from the original set, and all items from the specified set.
un1 = {20,30,40,50,60,70}
un2 = {10,20,50,60,90,75}
print(un1 | un2)    
               
Q54. What is intersection() in sets? Explain via code.
Answer->  The intersection() method returns a set that contains the similarity between two or more sets.              
un1 = {20,30,40,50,60,70}
un2 = {10,20,50,60,90,75}
print(un1 & un2)               
               
Q55. What is dictionary ibn Python?
Answer-> Dictionary is a collection of elements where each element is stored as key and value pair and defined within breces {}.
               
Q56. How is dictionary different from all other data structures.
Answer-> dictionary different from all other because each item being a pair in the form key:pair               
               
               
Q57. How can we delare a dictionary in Python?
Answer-> dict1 = {"name":"Amman","age":23,"country":"India"}
             
Q58. What will the output of the following?  
var = {}
print(type(var))
Answer-> <class 'dict'>             
 
Q59. How can we add an element in a dictionary?
Answer-> dict1 = {}
dict1 ["Name"] = "Amman"
dict1 ["age"]  = 23
dict1 ["country"] = "India"
               
Q60. Create a dictionary and access all the values in that dictionary.
Answer-> 
dict1 = {}
dict1 ["Name"] = "Amman"
dict1 ["age"]  = 23
dict1 ["country"] = "India"         
for i,j in dict1.items():
    print(i,j)
               
Q61. Create a nested dictionary and access all the element in the inner dictionary.           
Answer-> dict2 = {"Name":"Amman","Skills":{"Java":"Spring","Python":"Django"},"Company":"XYZ"}
for i,j in dict2["Skills"].items():
    print(i,j)               
               
Q62. What is the use of get() function?

Answer-> The get() method returns the value of the item with the specified key.
               
Q63. What is the use of items() function?
Answer-> The items() method returns a list containing for each key value pair.              
               
Q64. What is the use of pop() function?
Answer-> The pop() method removes the specified item form the dictionary.
             
Q65. What is the use of popitems() function?
Answer-> The popitems() method removes the last inserted key-value pair
               
Q66. What is the use of keys() function?
Answer-> The keys() method returns a list containing the dictionary keys
               
Q67. What is the use of values() function?
Answer-> The values() returns a list of all the values in the dictionary
              
Q68. What are loops in Python?
Answer-> Loop is used to execute a satement or a number of statement for a specific no of times according to a condition.              
               
Q69. How many type of loop are there in Python?
Answer-> There are 2 types of loop in Python.
              
Q70. What is the difference between for and while loops?
Answer-> In while loop the statement of else block will execute when the condition of while loop will become false.
for in loop is used to iterate through a sequence it may be a list,string,tuple,dictionary,range() function etc.       
               
Q71. What is the use of continue statement?
Answer-> It is used to skip the rest of the statement inside a loop for the current iteration only.
               
Q72. What is the use of break statement?
Answer-> break keyword is used to terminate a loop.It can be used with while loop and for loop.
              
Q73. What is the use of pass statement?
Answer->It is used to create an empty block.it is used when we went to make a statement syntactically correct but does nothing.
               
Q74. What is the use of range() function?
Answer-> Used to generate a sequence of numbers with in a range.
range(start,stop,step)
               
Q75. How can you loop over a dictionary?
Answer-> 
dictionary1 = {
    "Lenovo":"I5 8th Gen",
    "HP":"I7",
    "Asus":"I3"
}    
for dicts in dictionary1:
    print(dicts)
               
Q76. Write a Python program to find the factorial of a given number.
Answer->      
def factorial(num):
    fact = 1
    for i in range(1,num+1):
        fact = fact * i  
        print(fact) 
factorial(5)               
                          
Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100
Answer->
def simpleintrest(p,r,t):
    SI = (p*r*t)/100
    print("Simple Intrest",SI)
    return SI
simpleintrest(8, 8, 6)               
               
Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.
Answer->  def CompundIntrest(p,r,t):
    a = p*(1+r/100)**t
    compundintrest = a -p
    print("Compund Intrest",compundintrest)
    return compundintrest
CompundIntrest(1200, 2, 5.4)          
   
Q79. Write a Python program to check if a number is prime or not.
Answer-> def Isprime(num):
    for i in range(2,num):
        if num%i==0:
            print(num,"is not a prime number")
            break
    else:
        print(num,"is a prime")
Isprime(5) 

Q80. Write a Python program to check Armstrong Number.
 Answer->              
def check_armstrong(num):
    sum = 0
    temp = num
    while temp > 0:
        digit = temp % 10
        sum +=digit ** 3
        temp //=10
    if num == sum:
        print(num,"is a armstrong number")    
    else:
        print(num,"is not a armstrong number")
check_armstrong(153) 

Q81. Write a Python program to find the n-th Fibonacci Number.
 Answer->              
def Fibonacci(number):
    if number <= 2:
        return number - 1
    else:
        return Fibonacci(number -1) + Fibonacci(number-2)
print(Fibonacci(8))                

Q82. Write a Python program to interchange the first and last element in a list.
Answer->               
def InterChange(changeList):
    changeList[0],changeList[-1] = changeList[-1],changeList[0]
    return changeList
print(InterChange([12,35,9,56,24]))

Q83. Write a Python program to swap two elements in a list.
 Answer->              
def swapProgram(list,position1,position2):
    list[position1],list[position2] = list[position2],list[position1]
    return list
    
list = [20,30,40,50]
position1,position2 = 1,2
print(swapProgram(list, position1-1, position2-1))   

Q84. Write a Python program to find N largest element from a list.
Answer->
def n_max_elements(list1, N):
	final_list = []

	for i in range(0, N):
		max1 = 0
		
		for j in range(len(list1)):	
			if list1[j] > max1:
				max1 = list1[j]
				
		list1.remove(max1)
		final_list.append(max1)
		
	print(final_list)

list1 = [2, 6, 41, 85, 0, 3, 7, 6, 10]
N = 2

n_max_elements(list1, N)

Q85. Write a Python program to find cumulative sum of a list.
Answer->
def sumList(lists):
    sum = 0
    for i in lists:
        sum += i
        print(sum)
lists=[10,20,30,40]
sumList(lists)

Q86. Write a Python program to check if a string is palindrome or not.
Answer->
def isPalindrome(name):
    if name == name[::-1]:
        print("The String is a palindrome")
    else:
        print("The String isn't a palindrome")    
isPalindrome("PHP") 
 
Q87. Write a Python program to remove i'th element from a string.               
Answer->
def removeElement(i):
  str1 = "Big Data Bootcamp"
  str2 = ""

  for n in range(len(str1)):
    if n == i:
      continue
    else:
      str2 = str2 + str1[n]

  return str2

print(removeElement(1))

Q88. Write a Python program to check if a substring is present in a given string.
Answer->
def check_String(string):
    if "message" in string:
        print(string,"Yes Present")
    else:
        print(string,"No its not present")
check_String("Hello message")

Q89. Write a Python program to find words which are greater than given length k.
Answer->
def word_k(k, s):    
    word = s.split(" ")
    for x in word:
        if len(x)>k:
          print(x)
k = 3
s ="Python is good to learn"
word_k(k, s)
Q90. Write a Python program to extract unquire dictionary values.
Answer->
dict_1 = {'learning': [5, 6, 7, 8],
             'is': [10, 11, 7, 5],
             'always': [6, 12, 10, 8],
             'good': [1, 2, 5]}
print("The original dictionary is : " + str(dict_1))
res = list(sorted({ele for val in dict_1.values() for ele in val}))
print("The unique values list is : " + str(res))
 
Q91. Write a Python program to merge two dictionary.               
Answer->
dict_1 = {'a': 10, 'b':20 }
dict_2 = {'c': 30, 'd': 40}

print(dict_1 | dict_2)

 OR              
               
def Merge(dict1, dict2):
	return(dict2.update(dict1))

dict1 = {'a': 10, 'b': 8}
dict2 = {'d': 6, 'c': 4}

print(Merge(dict1, dict2))

print(dict2)

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Answer->               
print(dict( [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]))

Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.
Answer->
list1 = [9,5,6]
tupleList = [(val,(val*val*val)) for val in list1]
print(str(tupleList))
               
Q94. Write a Python program to get all combinations of 2 tuples.               
Answer->
test_tuple1 = (7, 2)
test_tuple2 = (7, 8)

res = [(a, b) for a in test_tuple1 for b in test_tuple2]
res = res + [(a, b) for a in test_tuple2 for b in test_tuple1]

print("The Combination : ", str(res))

Q95. Write a Python program to sort a list of tuples by second item.
Input : [('452', 10), ('256', 5), ('100', 20), ('135', 15)]
Output : [('256', 5), ('452', 10), ('135', 15), ('100', 20)]
Answer->
def Sort_Tuple(tup):
     
    lst = len(tup)
    for i in range(0, lst):
         
        for j in range(0, lst-i-1):
            if (tup[j][1] > tup[j + 1][1]):
                temp = tup[j]
                tup[j]= tup[j + 1]
                tup[j + 1]= temp
    return tup
 
tup =[('452', 10), ('256', 5), ('100', 20), ('135', 15)]
       
print(Sort_Tuple(tup))              

Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 

Answer->
for i in range(1,6):
    for j in range(i):
        print("*",end="")
    print("")   
               
Q97. Write a python program to print below pattern.
    *
   **
  ***
 ****
*****
Answer->
def inverse_pattern():
  n=5;i=0
  while(i<=n):
    print(" " * (n - i) +"*" * i)
    i+=1
inverse_pattern()
               
Q98. Write a python program to print below pattern.
    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Answer-> def pattern(n):
      k = 2 * n - 2
      for i in range(0,n):
           for j in range(0,k):
               print(end=" ")
           k = k - 1
           for j in range(0, i+1):
                print("*", end=" ")
           print("\r")
 
pattern(5)              
               
Q99. Write a python program to print below pattern.
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 
Answer->           
for i in range(1,5):
    for j in range(i+1):
        j = j + 1
        print(j,end="")
    print("")                  
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
Answer->               
def patterns(n):  
    x = 65 
    for i in range(0,n):
        ch = chr(x)
        x +=1
        for j in range(0,i+1):
            print(ch,end="")  
        print()     
patterns(5)               
