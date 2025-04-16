
# Day_01



message = '''
Hi mark,

This is Anup Rai from xyz IT company

blah blah blah...............
'''



#sum of int numbers

def sum(a, b):
    return (a + b)

a=int(input("Enter value of a :-\n"))
b=int(input("Enter value of b :- \n"))

print(f'The sum of {a} and {b} is {sum(a, b)}')





#sum of int numbers

def sum(a, b):
    return (a + b)

a=float(input("Enter value of a :-\n"))
b=float(input("Enter value of b :- \n"))

print(f'The sum of {a} and {b} is {sum(a, b)}')




#switch_example

def switch_example(a, b,switch_value):
    match switch_value:
        case 1:
            print(f'The sum of {a} and {b} is {a+b}')
        case 2:
            print(f'The sub of {a} and {b} is {a-b}') 
        case 3:
            print(f'The multiplication of {a} and {b} is {a*b}')    
        case 4:
            if b != 0:
                print(f'The Division of {a} and {b} is {a/b}') 
            else:
                print("Division by Zero is not valid , Enter except ZERO value .............!!!!!!!")
                
        case _:
            print("Enter valid options only ( 1 to 4 only )")

a = int(input('Enter value of a :-\n'))
b = int(input('Enter value of b :- \n'))
switch_value = int(input('Choose one option:-\n'
'Enter 1 for Addition\n'
'Enter 2 for Subtraction\n'
'Enter 3 for Multiplication\n'
'Enter 4 for Division\n'))

switch_example(a, b,switch_value)






