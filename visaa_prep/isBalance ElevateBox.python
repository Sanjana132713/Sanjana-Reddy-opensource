n=int(input())
a=list(map(int,input().split()))
b=[]
for i in range(0,n):
    leftweight=sum(a[:i])
    rightweight=sum(a[i+1:])
    bw=abs(leftweight-rightweight)
    b.append(bw)
print(" ".join(map(str,b)))
