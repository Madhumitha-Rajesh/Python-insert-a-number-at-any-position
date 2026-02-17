# Python-insert-a-number-at-any-position

numbers = [3,4,1,9,6,2,8]
print(numbers)
x = int(input("Enter the number to be inserted: "))
y = int(input("Enter the position: "))
numbers.insert(y,x)
print(numbers)


Output-

[3, 4, 1, 9, 6, 2, 8]
Enter the number to be inserted: 4
Enter the position: 3
[3, 4, 1, 4, 9, 6, 2, 8]
