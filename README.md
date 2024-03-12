n=int(input())
d={}
for i in range(1,n+1):
  res=0 
  for j in range(1,i+1):
    res=res+j 
  d[i]=res
print(d)
