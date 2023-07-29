# Python
#Menu based Calculator

#To Add
def add(num1,num2):
    result=num1+num2
    print("The Sum is: ",result)


#To Subtract
def subtract(num1,num2):
    if num1<num2:
        print(num1,"is lesser than",num2)
    else:
        result=num1-num2
        print("The Differnce is: ",result)
    

#To Multiply
def multiply(num1,num2):
    result=num1*num2
    print("The product is: ",result)

#To divide
def divide(num1,num2):
    if num1<num2:
        print("Division not possible")
    else:
        result=(num1/num2)
        print("The Quotient is: ",result)

#main



while True:
    print("\nMenu")
    print('1.Add')
    print('2.Subtract')
    print('3.Multiply')
    print('4.Divide')
    print('5.Exit')
    ans=int(input("Enter Option number to proceed: "))
    if ans==1:
        x=int(input("Enter first number: "))
        y=int(input("Enter Second number: "))
        add(x,y)
        
    elif ans==2:
        x=int(input("Enter first number: "))
        y=int(input("Enter Second number: "))
        subtract(x,y)
        
    elif ans==3:
        x=int(input("Enter first number: "))
        y=int(input("Enter Second number: "))
        multiply(x,y)
        
    elif ans==4:
        x=int(input("Enter first number: "))
        y=int(input("Enter Second number: "))
        divide(x,y)
        
    elif ans==5:
        print("Thank you")
        break
    
    else:
        print("Invalid Input")
