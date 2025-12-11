# Second_largest.py
a = []
n = int(input("Enter number of elements:"))
for i in range(1,n+1):
    b = int(input("Enter element:"))
    a.append(b)
a.sort()
print("Second largest element is:", a[n-2])


Output:
Enter number of elements:5
Enter element:10
Enter element:4
Enter element:24
Enter element:31
Enter element:16
Second largest element is: 24
