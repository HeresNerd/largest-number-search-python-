# largest-number-search-python-
A simple number search algorithm made in Python.
--------------------------------------------------
def max_num(num1, num2, num3):
  if num1 >= num2 and num1 >= num3:
    return num1
  elif num2 >= num1 and num2 >= num3:
    return num2
  else:
    return num3

print("LARGEST NUMBER GUESSER by Nikoli Loren")
x = input("Enter first number: ")
y = input("Enter second number: ")
z = input("Enter third number: ")
print("The largest number you entered was " + max_num(x, y, z))
