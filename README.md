# 17-03-2022-assignment-1
#program to remove vowels from the given string
s=input()
l=list(s)
x=[]
for i in l:
    if i=='a' or i=='e' or i=='o' or i=='u' or i=='A' or i=='E' or i=='O' or i=='i' or i=='I' or i=='U':
        continue
    else:
        x.append(i)
for i in x:
    print(i,end='')
