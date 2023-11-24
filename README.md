# power
#To calculate power using recursion
def pow(n, p):
    if p == 1:
        return n
    else:
        return n * pow(n, p - 1)

# Taking user input for the base and exponent
n = int(input("Enter the value of the base: "))
p = int(input("Enter the value of the exponent: "))

# Calling the pow function and printing the result
result = pow(n, p)
print(f"{n} raised to the power {p} is: {result}")
