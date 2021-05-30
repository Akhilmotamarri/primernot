# primernot
def primernot(n):
    l=[]
    if n>1:
        if n==2:
            return 1
        for i in range(2,n):
            if n%i==0:
                for i in range(2,n+1):
                    if n%i==0:
                        l.append(i)
                return l[0]
                break
            else:
                return 1;
s=primernot(2)
print(s)
