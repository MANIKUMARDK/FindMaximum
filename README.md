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

Developed by : MANIKUMAR D.K

Register number : 212223230121

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
max=list1[0]
for i in list1:
if i>max:
max=i
return max

```

## Output:
### SORT()
![Screenshot 2024-04-07 215606](https://github.com/MANIKUMARDK/FindMaximum/assets/147215581/49ef61b2-edd1-4f58-8b96-032d7f75b56f)

### MAX()
![Screenshot 2024-04-07 215626](https://github.com/MANIKUMARDK/FindMaximum/assets/147215581/14f2fab3-e019-473d-86be-a70db09fb39f)


### BUILTIN FUNCTION
![Screenshot 2024-04-07 215642](https://github.com/MANIKUMARDK/FindMaximum/assets/147215581/7ee984cf-675d-40e4-a394-d9d5a1157e7d)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
