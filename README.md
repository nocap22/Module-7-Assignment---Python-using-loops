# Creating a list of 15 numbers
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]

# Looping through the list of numbers
for number in numbers:
    # Check if the number is even
    if number % 2 == 0:
        print(str(number) + " is even")
    else:
        print(str(number) + " is odd")
