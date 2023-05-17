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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Shalini.k
RegisterNumber: 212222240095
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Shalini.k
RegisterNumber: 212222240095
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Shalini.k
RegisterNumber: 212222240095
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number>max):
            max=number
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (135)](https://github.com/shalinikannan23/FindMaximum/assets/118656529/7ba57520-5671-41bd-b7bd-a2ab57694c94)
![Screenshot (137)](https://github.com/shalinikannan23/FindMaximum/assets/118656529/30f7c55b-b269-4696-bafe-9c59d0a3985c)
![Screenshot (135)](https://github.com/shalinikannan23/FindMaximum/assets/118656529/341fa002-9927-4b7c-8288-a81d16cf8848)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
