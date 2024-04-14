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
Program to mark the maximum of marks using the list method sort   
Developed by: EASWAR R     
RegisterNumber: 212223230053  
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: EASWAR R
RegisterNumber: 212223230053
def max_marks(marks):
     large=max(marks)
     return large
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: EASWAR R
RegisterNumber: 212223230053
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max        
```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/EaswarR2005/FindMaximum/assets/146931525/09ca612e-c890-43c5-a113-13b339525feb)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/EaswarR2005/FindMaximum/assets/146931525/f6c7818c-97fb-431b-b622-bcd182da0e25)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/EaswarR2005/FindMaximum/assets/146931525/fbae2222-6d75-4b3a-a334-fd335f1122b8)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
