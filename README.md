# Quadratic-Equation


import math



a=int(input("number a:"))
b=int(input("number b:"))
c=int(input("number c:"))



print(str(a)+"x*x +"+str(b)+"x +"+str(c)+"=0")
d=b*b-4*a*c

print(d)



if d==0:
    x=(-b / 2*a)
    print("The Equation has one answer:"+str(x))
elif d<0:
    print("The equation has not any answer")
else:
    x1=(-b + math.sqrt(d))/(2*a)
    x2=(-b - math.sqrt(d))/(2*a)
    print("The Equation has two answer:  "+"x1= "+str(x1)+"  and  "+"x2= "+str(x2))
