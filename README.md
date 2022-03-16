# March-16-Ass-2
Assignment-2
s=input()
l=list(s)
e=[]
o=[]
res=[]
for i in l:
    i=int(i)
    if i%2==0:
        e.append(i)
    else:
        o.append(i)
res=o+e
for i in res:
    print(i,end='')
