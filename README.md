# Input from the user
num = int(input("Enter a number: "))

# Convert negative numbers to positive
num = abs(num)

# Check if the number is 0
if num == 0:
    count = 1
else:
    count = 0

    # Count the digits using a while loop
    while num > 0:
        num = num // 10   # Remove the last digit
        count += 1

# Display the result
print("Number of digits =", count)
