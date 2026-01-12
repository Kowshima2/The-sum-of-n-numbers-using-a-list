# The-sum-of-n-numbers-using-a-list
numbers = []
num = int(input('How many numbers: '))

for n in range(num):
    x = int(input('Enter number '))
    numbers.append(x)

print("Sum of numbers in the given list is:", sum(numbers))

output:
How many numbers: 4
Enter number 2
Enter number 4
Enter number 6
Enter number 8
Sum of numbers in the given list is: 20
