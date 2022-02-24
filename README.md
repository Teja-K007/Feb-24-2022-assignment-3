# Feb-24-2022-assignment-2

x=input()
l=x.split()
o=[]
e=[]
for i in l:
    i=int(i)
    if i%2==0:
        e.append(i)
    else:
        o.append(i)
print(o,' ',e)
