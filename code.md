r=(input("Please enter an integer for the upper limit."))

for a in range(2,int(r)+1):
    k=0
    for i in range(2,a//2+1):
        if(a%i==0):
          k=k+1
    if(k<=0):
        print(a)
print(r)

