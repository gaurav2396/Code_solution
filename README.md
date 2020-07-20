# Code_solution

nd = input().split()
n = int(nd[0])
d = int(nd[1])
a = list(map(int, input().rstrip().split()))
c =[]
e =[]
if d < n:
    for i in range(0,d):
        c.append(a[i])
    # print(c)    
    for i in range(d,n):
        e.append(a[i])
    # print(e)
    e += c
for i in range(len(e)):
    print(e[i],end = " ")  


            
