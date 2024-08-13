num1=int(input("enter 1st number"))
num2=int(input("enter 2nd number"))
choice=int(input("select choice: press 1 for addition(+), press 2 for substraction(-):, press 3 for multiplication(*), press 4 for division(/):"))
if choice==1:
 print("addition of",num1,"and",num2,"is",num1+num2)
elif choice==2:
 print("substractiion of",num1,"and",num2,"is",num1-num2)
elif choice==3:
 print("multiplication of",num1,"and",num2,"is",num1*num2)
elif choice==4:
 print("division of",num1,"and",num2,"is",num1/num2)
else:
  print("invalid choice")
