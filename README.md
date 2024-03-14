# Factors-of-a-given-number
'''
# Approach - 1
'''
n = int(input())
for i in range(1,n+1):
  if n%i==0:
    print(i,end=" ")
'''
# Approach - 2
'''
n = int(input())
i = 1
while i <= n:
  if n%i == 0:
    print(i,end=" ")
  i = i + 1
'''
# Approach - 3
'''
n = int(input())
a = []
for i in range(1,n+1):
  if n%i == 0:
    a.append(i)
for i in a:
  print(i,end=" ")
'''
# Approach - 4
'''
n = int(input())
a = []
for i in range(1,n+1):
  if n%i == 0:
    a.append(i)
print(*a,sep=" ")
