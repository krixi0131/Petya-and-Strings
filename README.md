# Petya-and-Strings
```python
a=str(input())
b=str(input())
check=0
for i in range(len(a)):
    x=ord(a[i])
    y=ord(b[i])
    if ord(a[i])<97:
        x+=32
    if ord(b[i])<97:
        y+=32
    if x>y:
        check=1
        break
    elif x<y:
        check=-1
        break
if check==1:
    print(1)
elif check==-1:
    print(-1)
else:
    print(0)
```
