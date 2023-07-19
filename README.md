f=open('24-1.txt').readline()
k=0
maxk=0 
for i in range(1,len(f)):
    if f[i]>f[i-1]:
        k+=1
        maxk=max(maxk,k)
    else:
        k=0
print(maxk)
