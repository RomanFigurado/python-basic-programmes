# Hotel-bill-tips-system
#just adding tips with hotel bill by customer satisfaction

y= float(input("Enter the  bill Amount: "))
x= float(input("Ask the diner to enter the cost of the meal: "))

if x== 1:
    print("The diner is totally satisfied")
    print("bill + tips = ", y+y*20/100)
    
elif x==2:
    print("The diner is satisfied ")
    print("bill + tips  = ", y+y*15/100)
elif x==3:
    print("The diner is dissatisfied ")
    print("bill + tips  = ", y+y*10/100)
else:
    print("invalid amount")
print("Thank you come again")    
