#1 Variables in Python

print("Enter First Name :-")
first_name = input()
print("Enter Last Name :-")
last_name = input()
print("Enter Age :-")
age = int(input())
print("Enter Your Country :-")
country = input()

print(f'Hello...!!!\nMy Name is {first_name} {last_name}\nI am {age} years old and I am from {country}')



#2 Example of loops in Python

print("First 10 natural number are :-")
for i in range (10):
    print(i+1)
    
print("Square of natural numbers are :-")
for i in range(10):
    print((i+1)**2)  

    
#3 Function in Python

def sum(a, b):
    return (a+b)    
print("Enter the first number :-")
a = int(input())
print("Enter the second number :-")
b = int(input())
print("Sum of two number is :-",sum(a, b))
sum(a, b)


#4 Function with multiple options

def switch_example(a, b,switch_value):
    match switch_value:
        
        case 1:
            print(f"The sum of {a} and {b} is {a+b}")
        case 2:
            print(f"The sub of {a} and {b} is {a-b}")
        case 3:
            print(f"The multiplication of {a} and {b} is {a*b}")
        case 4:
            if b != 0:
                print(f"The Division of {a} and {b} is {a/b}")
            else:
                print(f"Division by Zero is not valid , Enter except ZERO value .............!!!!!!!")
        case 5:
            print(f"The square of {a} is {a**2} and {b} is {b**2}")
        case _:
            print(f"Enter valid options only ( 1 to 5 only )")
                
print("Enter First Number :-")            
a = int(input())
print("Enter Second Number :-")
b = int(input())
print("Choose one option :- \nEnter 1 for Addition \nEnter 2 for Subtraction \nEnter 3 for Multiplication \nEnter 4 for Division \nEnter 5 for square")
switch_value = int(input())
switch_example(a, b,switch_value)
    
