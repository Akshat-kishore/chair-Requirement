# chair-Requirement
# cook your dish here
a=int(input())
for i  in range(a):
    x,y=map(int,input().split())
    if (x>y):
        print(x-y)
    if(x==y):
        print(x-y)
    if(x<y):
        print(0)
