# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
'''
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: Pravinrajj G.K
RegisterNumber: 212222240080
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: Pravinrajj G.K
RegisterNumber: 212222240080
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):

    max1=marks[0]
    for i in marks:
        if i>max1:
            max1 = i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])
''' 
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: Pravinrajj G.K
RegisterNumber: 212222240080
'''

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output1](https://github.com/Pravinrajj/FindMaximum/assets/117917674/bc0e9dd4-a82b-4974-9a14-2c380173aafa)
![output2](https://github.com/Pravinrajj/FindMaximum/assets/117917674/5f338fd0-d134-4003-9814-8bd74b106b1b)
![output3](https://github.com/Pravinrajj/FindMaximum/assets/117917674/901d0fcf-676c-4601-bc58-902f3d99d68b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
