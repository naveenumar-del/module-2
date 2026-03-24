Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

Aim:

To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

Algorithm:

Start the program.

Input the number of rows from the user.

Loop from 0 to the number of rows.

For each row:

Print appropriate spaces to shape the triangle.

Compute values using the formula:

[ C(n, k) = \frac{n!}{k!(n-k)!} ]

Print all rows of Pascal’s Triangle.

End the program.

 Program:

Add Code Here

def pas(n):
    
    for i in range(n):
    
        print(" "*(n-1-i),end="")

        a=1

        for j in range(i+1):

            print(a,end=" ")

            a=a*(i-j)//(j+1)
        print()
n=int(input())
pas(n)

Sample Output

<img width="1148" height="581" alt="image" src="https://github.com/user-attachments/assets/05f0ad9d-5edc-42a8-af21-b13c1f935a37" />


Result
The program successfully generates Pascal's Triangle with the specified number of rows, using the appropriate formula for combination values.
