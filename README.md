# Simple_Calculator
num1= int (input ("Enter the first value:"))
operator= input ("Enter operator(+,-,*,/,%):")
num2= int (input ("Enter the second value:"))
if operator =="+":
    print (num1+num2)
elif operator =="-":
    print (num1-num2)
elif operator ==  "*":
    print (num1*num2)
elif operator == "/":
    print (num1/num2)
elif operator =="%":
    print (num1%num2)
else:
    print ("Invalid Operation")
