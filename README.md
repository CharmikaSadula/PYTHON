# Type casting trials
a="10"
b="30"
a=int(a)
b=int(b)
c=a+b
print(a)
print(a,type(a))

#output
10
(10, <class 'int'>)


x=input("Enter the number you want to multiply:")
x=int(x)
print(x,type(x))
y=10
z=x*y
print(z,type(z))

#output
Enter the number you want to multiply: 20
(20, <class 'int'>)
(200, <class 'int'>)


a=input("Enter your name:")
a=str(a)
b=input("Enter your college id no:")
b=float(b)
c=input("Enter your roll no:")
c=int(c)
d=input("Are you above 18:True")
d=bool(d)

print(a,type(a))
print(b,type(b))
print(c,type(c))
print(d,type(d))
#output
Enter your name: charmika
Enter your college id no: 2001.4001
Enter your roll no: 23
Are you above 18:True 
('charmika', <class 'str'>)
(2001.4001, <class 'float'>)
(23, <class 'int'>)
(False, <class 'bool'>)
