# reverse_any-number
num=int(input("enter the number to be reversed"))
rev=0
while num !=0:  #using while loop
    digit=num%10
    rev=rev*10+digit
    num//=10
print("reverse of the number is:",rev)  #print the result
    
