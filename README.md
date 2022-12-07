# Repository3
n=int(input("enter the no"))
count=0
for i in range(2,n):
    if n%i==0:
        count+=1
if count==0:
            print("it is a prime number")
else:
    print("it is not a prime number")
