x = int(input("How many numbers do you need to check? ")) 
c=0
w=0
for i in range(x):
    y = int(input("Enter number: "))
    if y == 0: 
        print(str(y)+" is not divisble by 3.")
        w+=1
    else:
        if y%3 == 0:
            print(str(y)+" is divisble by 3.") 
            c+=1
        else: 
            print(str(y)+" is not divisble by 3.") 
            w+=1   
    
print("You entered "+str(c)+" number(s) that are divisible by 3.")
print("You entered "+str(w)+" number(s) that are not divisible by 3.")
