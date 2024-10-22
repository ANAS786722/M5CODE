# M5CODE
HERE IS MY IN CLASS 5TH ASSIGNEMENT!
# Anas Mohammed
# 2024-10-22
# This program prints an annoying message 100 times.

for i in range(100):
    print("This is an annoying message!")

# Anas Mohammed
# 2024-10-22
# This program checks if numbers from a list are even or odd.

numbers = [12, 37, 5, 42, 8, 3, 29, 14, 11, 24]  # Example numbers from random.org

for number in numbers:
    if number % 2 == 0:
        print(f"Hey - {number} is even!")
    else:
        print(f"Gosh, {number} is odd!")

# Anas Mohammed
# 2024-10-22
# This program prints messages for numbers from 1 to 50, checking divisibility.

for i in range(1, 51):
    if i % 3 == 0 and i % 5 == 0:
        print("Divisible by both")
    elif i % 3 == 0:
        print("Divisible by three")
    elif i % 5 == 0:
        print("Divisible by five")
    else:
        print(i)

