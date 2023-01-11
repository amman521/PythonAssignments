Q1. What is the purpose of Python's OOP?
Answer-> 
Python is an object-oriented programming language. And, like other OOP languages, it also supports the concept of objects and classes.
Object-Oriented Programming makes the program easy to understand as well as efficient.

Q2. Where does an inheritance search look for an attribute?
Answer-> 
An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right. The search stops at the first place the attribute is found.

Q3. How do you distinguish between a class object and an instance object?
Answer-> A class is a blueprint or prototype from which objects are created. An instance is a single and unique unit of a class. 

Q4. What makes the first argument in a class’s method function special?
Answer-> The first parameter of a function in class must be the object itself and usually called 'self' by convention.

Q5. What is the purpose of the init method?
Answer-> The __init__() function is called automatically every time the class is being used to create a new object.
Q6. What is the process for creating a class instance?

Q6. What is the process for creating a class instance?
Answer-> you call the class using class name and pass in whatever arguments its __init__ method accepts.

Q7. What is the process for creating a class?
Answer-> class iNeuron():
<!-- write codes and method inside it -->

Q8. How would you define the superclasses of a class?
Answer-> The class from which a class inherits is called the parent or superclass.

Q9. What is the relationship between classes and modules?
Answer-> The difference between a class and a module in python is that a class is used to define a blueprint for a given object, whereas a module is used to reuse a given piece of code inside another program.

Q10. How do you make instances and classes?
Answer->  Instance is an object that belongs to a class.
Every object has a type and the object types are created using classes.

Q11. Where and how should be class attributes created?
Answer-> Class attributes are the variables defined directly in the class that are shared by all objects of the class.

Q12. Where and how are instance attributes created?
Answer-> Instance attributes are accessed through object name.
class Employee:    
    id = 10   
    name = "John"    
    def display (self):    
        print("ID",self.id,"name",self.name))     
emp = Employee()    
emp.disp

Q13. What does the term "self" in a Python class mean?
Answer-> Self is not a keyword it refers to the current object.

Q14. How does a Python class handle operator overloading?
Answer-> Python operator overloading handle arithmetic operator as well as comparison operator.

Q15. When do you consider allowing operator overloading of your classes?
Answer-> When one or both operands are of a user-defined class or structure type, operator overloading makes it easier to specify user-defined implementation for such operations.

Q16. What is the most popular form of operator overloading?
Answer-> most popular form is addition operator and for two string concatination.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
Answer-> The Most important concept to grasp are Inheritance and Polymorphismin order to comprehend pyhton in object oriented programming.

Q18. Describe three applications for exception processing.
Answer-> try,exception,finally.

Q19. What happens if you don't do something extra to treat an exception?
Answer-> The program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?
Answer-> You can use else block.

Q21. Describe two methods for triggering exceptions in your script.
Answer-> Try – This method catches the exceptions raised by the program. Raise – Triggers an exception manually using custom exceptions.

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of whether or not an exception exists.
Answer-> Finally block always executes irrespective of an exception being thrown or not.

Q23. What is the purpose of the try statement?
Answer-> The try block lets you test a block of code for errors while being executed.

Q24. What are the two most popular try statement variations?
Answer-> else finally .

Q25. What is the purpose of the raise statement?
Answer-> Raise is a keyword used to raise an exception explicitly by programmer.

Q26. What does the assert statement do, and what other statement is it like?
Answer-> The assert keyword is used when debugging code.
The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError.

Q27. What is the purpose of the with/as argument, and what other statement is it like?
Answer-> with statement helps avoiding bugs and leaks by ensuring that a resource is properly released when the code using the resource is completely executed.

Q28. What are *args, **kwargs?
Answer-> *args enable us to pass the varibale number of non-keyword arguments to functions, but we cannot use this to pass keyword argument.**kwargs mean that they contain a ke-value pair like dictionary.

Q29. How can I pass optional or keyword parameters from one function to another?
Answer-> By using keyword arguments.

Q30. What are Lambda Functions?
Answer-> A lambda function is a small anonymous function.
x = lambda a: a + 10
print(x(5))

Q31. Explain Inheritance in Python with an example?
Answer-> It is a technique by which properties of parent are transmitted to children.
 class A:
       def displ(self):
              print("parent class")

class B(A):
      def show(self):
          print("child class")
ob =  B()
ob.disp()
ob.show()

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?
Answer-> Multi level Inheritance.

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
Answer-> isinstance() function.

Q34.Explain the use of the 'nonlocal' keyword in Python.
Answer-> nonlocal to declare that the variable is not local.

Q35. What is the global keyword?
Answer-> When a local variable and global variable have same name, we cant access the global variable inside the function.But outside the function it is accessible.
If we want to use the global variable inside a function we have to use the keyword global.








