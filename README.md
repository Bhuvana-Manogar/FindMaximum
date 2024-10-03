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
#developed by:Bhuvaneshwari M
#register number:212223230033

def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```
#developed by:Bhuvaneshwari M
#register number:212223230033

def max_marks(array):
    return max(array)
```

iii) # To find the maximum marks without using builtin functions.
```
#developed by:Bhuvaneshwari M
#register number:212223230033

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1
```



## Output:
![Screenshot 2024-10-03 105959](https://github.com/user-attachments/assets/1e8a9432-0e2e-4f8d-8ab0-578666ef50c1)
![Screenshot 2024-10-03 110024](https://github.com/user-attachments/assets/5fb0a5b4-12d5-4c5d-a173-667b1ce7cddb)
![Screenshot 2024-10-03 110047](https://github.com/user-attachments/assets/d6c70a33-7993-4d4e-91dc-c0b9c7a6682c)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
