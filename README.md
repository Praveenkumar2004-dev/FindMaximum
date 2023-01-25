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
Find-the-maximum-of-a-list-of-numbers
Developed by: PRAVEENKUMAR S
Ref no:22004035

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
   large = max(marks)
   return large
   
```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```
## Sample Input and Output
USING LIST METHOD SORT:
![listmethodsort](https://user-images.githubusercontent.com/119559827/214597273-4967a4d6-ba8e-4a08-9b28-ff836b2c6bfc.png)
USING LIST METHOD MAX:
![listmethodmax](https://user-images.githubusercontent.com/119559827/214597442-8011ae4c-1f8f-4fb3-aa69-5c5f1b89f4d6.png)
USING BUILT-IN FUNCTION:
![buildinfunction](https://user-images.githubusercontent.com/119559827/214597574-be6a5750-03d9-438f-9c84-2d7702b065e7.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
