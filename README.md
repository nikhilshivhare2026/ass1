# ass1
# project 1.
f=open("f1.txt","r")
i=0
j=0
for x in f :
    for y in x: 
     if y.isalnum():
        i+=1
     if y.isalpha():
        j+=1
print("total letter",j)
print("total num",i)
# pro 2.
f=open("f2.txt","r")
i=0
j=0
for x in f:
    for y in x:
        if y.isupper():
            i+=1
        if y.islower():
            j+=1
print("capital letter",i)
print("lower letter",j)
#pro 3.
a = input("Enter a digit: ")
result = int(a) + int(a * 2) + int(a * 3) + int(a * 4)
print("Result:", result)
