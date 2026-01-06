print("hey")

# practice


print("Raj")

name = input("Enter your name : ");
print(name)

age = input("Enter your age : ");
print(age)

a = 3
b = 2.5
c = 6
d = a+c-b
print(d)

from typing_extensions import TypeForm
a = 3
b = 2.5
c = 6
d = a+c-b
e = d+a
print(e)
print(type(e))

a = 123
print(type(a))
b=4.5
c=3
d=b+c-2
print(d)
print(type(d))
e=("hey")
print(type(e))
f=["hello"]
print(type(f))
g={"how are you"}
print(type(g))
h={12,15,18}
print(type(h))

print(b>=c)
print(d>b,d<c)
print(type(b))

#create an integer age=25. print a message saying: "I am [age] years old " using str() to combine them.

age = input("Enter your age : ")
print("I am " + str(age) + " years old")



#Convert the number 0 into a boolean. Then convert the number 1 into a boolean.Print 1

print (bool(0) , bool(1) )
print(bool(4) , bool(2))

# Ask the user for a number using input(), multiply it by 2 before and after typecasting the input to int, and print the result.

a = input("Enter the no: ")
print (int(a) * 2)

# Take a string "15.7". Convert it to a float first, then to an int.

str = 15.7
print(int(str))
print(float(str))


# Create a list: my data = [1, 2, 3]. Convert this list into a Tuple.

data = tuple ([1 , 2 , 3])
print ( data , type ( data ) )


# Convert an empty string "" and a string with a space " " to Booleans.
print(bool("") , bool(" "))

# Convert the float 9.99 to an int and add it to the string "5" after converting to an int.

float = 9.99
str = 5
print(int(float) + str)
