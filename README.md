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
def max_marks(mark):
    mark.sort()
    large=mark[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(list1):
    large=max(list1)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(m):
    large=0
    for i in m:
        if i>large:
            large=i
    return large
```

## Output:
### using sort():
![Screenshot 2024-03-27 175406](https://github.com/mercyarulappan/FindMaximum/assets/149233730/8409df35-9e16-47df-9f79-0464e6acaa4a)
### using max():
![Screenshot 2024-03-27 175421](https://github.com/mercyarulappan/FindMaximum/assets/149233730/69b0e162-50e3-4b36-9c6b-b1f79f3b6d5f)
### not using built in functions:
![Screenshot 2024-03-27 175434](https://github.com/mercyarulappan/FindMaximum/assets/149233730/7d4510e6-0366-43dc-adae-b1069f90b4dd)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
