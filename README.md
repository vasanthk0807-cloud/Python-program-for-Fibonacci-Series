# Python-program-for-Fibonacci-Series(pls click on edit option to view code in proper way)
n = int(input("How many terms? "))
a = 0
b = 1
next = b  
count = 1

while count <= n:
    print(next, end=" ")
    count += 1
    a, b = b, next
    next = a + b
print()
