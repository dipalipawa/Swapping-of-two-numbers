# Swapping-of-two-numbers
#Swapping of two number without using any temporary variable in different ways in python
# Way 1 -
num1 = 10
num2 = 30
print("Before swapping") 
print(f"num1 = {num1}")
print(f"num2 = {num2}")

num1,num2 = num2,num1 #swapping logic
print("After swapping")
print(f"num1 = {num1}")
print(f"num2 = {num2}")

# way 2 -
num1 = 10
num2 = 20
print("Before swapping") 
print(f"num1 = {num1}")
print(f"num2 = {num2}")

#swapping logic
num1 = num1 + num2
num2 = num1 - num2
num1 = num1 - num2

print("After swapping")
print(f"num1 = {num1}")
print(f"num2 = {num2}")

