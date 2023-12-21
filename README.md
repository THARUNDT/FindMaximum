# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:	
Get the list of marks as input
### Step2:	
Use the sort() function or max() function or use the for loop to find the maximum mark.
### Step3:
Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
''' 
# Program to mark the maximum of marks using the list method sort
# Developed by: THARUN D
# RegisterNumber:23013993 
'''
~~~
def max_marks(marks):
    marks.sort()
    return marks[-1]
~~~
ii)	# To find the maximum marks using the list method max().
''' 
# Program to find the maximum marks using the list method max().
# Developed by: THARUN D
# RegisterNumber: 23013993
'''
~~~
def max_marks(marks):
    return max(marks)
~~~
iii) # To find the maximum marks without using builtin functions.
''' 
# Program to the maximum marks without using builtin functions.
# Developed by: THARUN D 
# RegisterNumber: 23013993
'''
~~~
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
~~~


## Output:
![Screenshot 2023-12-21 211536](https://github.com/THARUNDT/FindMaximum/assets/144871537/ab43b5c7-06fa-4aa2-93c7-dfb96232e3f2)
![Screenshot 2023-12-21 211554](https://github.com/THARUNDT/FindMaximum/assets/144871537/d3350efe-ae47-44f8-8f36-72ddf00f6dfe)
![Screenshot 2023-12-21 211609](https://github.com/THARUNDT/FindMaximum/assets/144871537/44e7204b-3dbd-4f16-973f-2b7cc6507be0)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
