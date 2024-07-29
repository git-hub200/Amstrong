# Amstrong
num=int(input("Enter a number: "))
temp=num
sum=0
while num>0:
    digit=num%10
    sum+=digit**3
    num=num//10
if temp==sum:
    print(f"{temp} is an Amstrong Number")
else:
    print(f"{temp} is not an Amstrong Number")
