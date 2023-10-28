value_1=int(input("enter a value 1:"))
value_2=int(input("enter a value 2:"))
value_3=int(input("enter a value 3:"))
value_4=int(input("enter a value 4:"))
print("Before Exchange:",value_1,value_2,value_3,value_4)

value_5=value_4
value_4=value_1
value_1=value_2
value_2=value_3
value_3=value_5

print("After Exchange:",value_1,value_2,value_3,value_4)
