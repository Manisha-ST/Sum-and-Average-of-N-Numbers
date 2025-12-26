# Sum-and-Average-of-N-Numbers

n = int(input("Enter the Limit: "))
s = 0

for i in range(1, n + 1):
    print("Enter", i, end=" ")
    a = int(input("th number: "))
    s = s + a

avg = s / n
print("The sum of entered numbers:", s)
print("The average of entered numbers:", avg)

Output:
Enter the Limit: 3
Enter 1 th number: 10
Enter 2 th number: 20
Enter 3 th number: 30
The sum of entered numbers: 60
The average of entered numbers: 20.0
