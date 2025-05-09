a=int(input())
b=int(input())
a=a*b
b=a/b
a=a/b
print(round(a),round(b))




a=int(input())
b=int(input())
a=a^b
b=a^b
a=a^b
print(a,b)
print(round(a),round(b))



p=float(3.14159)
r=float(7.5)
a=p*r**2
c=2*p*r
print(a,c)


from math import sin,cos,tan,radians
angle=30
print("sin:",sin(radians(angle)))
print("cos:",cos(radians(angle)))
print("tan:",tan(radians(angle)))
