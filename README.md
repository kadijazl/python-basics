### Python Basics 

#### Some details on shallow copy & deep copy
x = [1,2,3]
y = x # y is a reference of x
y.append(4)
print(x) # [1,2,3,4]

