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
Developed by: SARAVANA KUMAR
RegisterNumber: 212222230133
'''
def max_marks(marks):
    marks.sort()
    return marks[-1] 
```



ii)	# To find the maximum marks using the list method max().

```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SARAVANA KUMAR
RegisterNumber: 212222230133
'''
def max_marks(marks):
    return (max(marks)) 
```


iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: SARAVANA KUMAR
RegisterNumber: 212222230133
'''
def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        
```



## Output:

![Screenshot 2023-10-29 210819](https://github.com/Saravana-kumar369/FindMaximum/assets/117925254/4b873549-39da-441d-965d-d4e20ada0c66)

![Screenshot 2023-10-29 210850](https://github.com/Saravana-kumar369/FindMaximum/assets/117925254/2194ab85-f894-43da-93da-137e25e43881)

![Screenshot 2023-10-29 210908](https://github.com/Saravana-kumar369/FindMaximum/assets/117925254/c2d20d1c-5153-4f18-a29a-eee673b348e1)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
