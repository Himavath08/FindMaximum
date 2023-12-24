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
Program to mark the maximum of marks using the list method sort
Developed by:M Himavath
RegisterNumber: 23010121
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
   
   



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: M Himavath
RegisterNumber: 23010121
'''
def max_marks(marks):
    return max(marks)
   
    


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: M Himavath
RegisterNumber: 23010121
'''
def max_marks(list1):
    return max(list1)



```
 

## Output:
1)
![Screenshot 2023-12-25 004901](https://github.com/Himavath08/FindMaximum/assets/139110631/4bb86c1c-793a-4ffc-acef-5a5e008e4268)

2)
![Screenshot 2023-12-25 004909](https://github.com/Himavath08/FindMaximum/assets/139110631/1dc016b3-aa5e-49e0-bd8a-9982255ec065)

3)
![Screenshot 2023-12-25 004916](https://github.com/Himavath08/FindMaximum/assets/139110631/645f095c-1c98-492c-89ff-a5d1d16528d0)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
