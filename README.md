# Pattern
rows = int(input("Enter number of rows: "))
for i in range(0, rows, 2):
    star = rows - i
    space = i//2
    print(" " * space, "*" * star, )
