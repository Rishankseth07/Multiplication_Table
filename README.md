# Multiplication_Table

print("Mutiplication Table of Number")
print("\n")

num1 = int(input("Enter the number: "))
print("-"*25)

i = 1

while i in range(0,16):
    a = num1 * i
    print(num1, " * ", i ," = " ,a)
    i = i + 1
print("-"*25)
