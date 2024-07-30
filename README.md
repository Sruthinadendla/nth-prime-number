# nth-prime-number
n=int(input())
c,i=0,2
while c!=1:
  flag=True
  for i in range(2,i//2+1):
    if i%j==0:
      flag=False
      break
  if flag:
      c+=1
  i+=1
print(i-1)
