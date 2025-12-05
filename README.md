a=[]
n=int(input("Enter number of elements:"))
for i in range(1,n+1):
  b=int(input("Enter element:"))
  a.append(b)
a.sort()
print("Second largest element is:",a[n-2])


OUTPUT:
Enter number of elements:12
Enter element:15
Enter element:25
Enter element:16
Enter element:24
Enter element:54
Enter element:38
Enter element:89
Enter element:34
Enter element:11
Enter element:36
Enter element:22
Enter element:30
Second largest element is: 54
