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
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    maxi=max(marks)
    return maxi


```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
           max=i
    return max


```
# Sample Input and Output
#![Sam Max](https://github.com/abinayasangeetha/FindMaximum/assets/119393675/d45409be-ca0d-4a7c-8fc2-6cd0e43b8cdf)



## Output:
![Max out](https://github.com/abinayasangeetha/FindMaximum/assets/119393675/633ef094-6a07-4993-b55b-3a34a54ce28e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
