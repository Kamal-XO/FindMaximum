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
Developed by: Kamal
RegisterNumber: 22001133

def max_marks(marks):
    marks.sort()
    return marks[-1]
```
## output1:
![OUTPUT](./Outputmax1.png)


ii)# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Kamal
RegisterNumber: 22001133
'''
def max_marks(marks):
    large = max(marks)
    return large


```
## Output2:

![OUTPUT](./Outputmax2png)


iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Kamal
RegisterNumber: 22001133
'''
def max_marks(list1):
    max1 = list(0)
    for i in list1:
        if i > max1:
            max1 = i
    return max1
```

## Output 3:
 ![OUTPUT](./Output3.png)

## Sample Input and Output
![output](./img/max_marks1.jpg) 


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.