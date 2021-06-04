# prime-number
n=int(input("enter any number"))
l=int(input(" to enter any number"))
f=0
print("prime number is")
while n!=l:
 for i in range(2, n-1):
     if n%i==0:
          f=1
 if f==0:
    
    print(n)
 else:
     f=0
 n=n+1     
