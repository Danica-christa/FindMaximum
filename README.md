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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(marks):
    maximum=marks[0]
    for i in marks:
        if(i>maximum):
            maximum=i
    return maximum 
```
Program developed by : Danica Christa

Register No : 212223240022


## Output:
![alt text](<Screenshot 2024-03-29 162416.png>)
![alt text](<Screenshot 2024-03-29 162432.png>)
![alt text](<Screenshot 2024-03-29 162447.png>)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
