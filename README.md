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
Developed by: Sanjay siavaramakrishnan
RegisterNumber: 23013798
'''
def max_marks(marks):
    marks.sort()
    max=marks[0];
    for i in marks:
        if(i>max):
            max=i
    return max;
     


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Sanjay sivaramakrishnan
RegisterNumber: 23013798
'''
def max_marks(marks):
     return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Sanjay sivaramakrishnan
RegisterNumber: 23013798
'''
def max_marks(marks):
    max=0;
    for i in marks:
        if(i>max):
            max=i
    return max;
     


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/sanjaysivaramakrishnan/FindMaximum/assets/151629616/d46162da-151a-4379-a20d-2d0d94e682c5)
![image](https://github.com/sanjaysivaramakrishnan/FindMaximum/assets/151629616/626b58d1-92b6-40f6-9aac-4c1f73f6cca1)
![image](https://github.com/sanjaysivaramakrishnan/FindMaximum/assets/151629616/4a62164f-66d3-4ffd-b25a-44e04a6acab3)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
