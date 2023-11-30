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
Developed by: PREM.R
RegisterNumber: 23002486

def max_marks(marks):
    marks.sort()
    large= marks[-1]
    return large
    



```

ii)	# To find the maximum marks using the list method max().
```
Developed by: PREM. R
RegisterNumber: 23002486
def max_marks(marks):
    large = max(marks)
    return large




```

iii) # To find the maximum marks without using builtin functions.
```
Developed by: PREM.R 
RegisterNumber: 23002486
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max    
    



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![sorting 1](https://github.com/PREM3112/FindMaximum/assets/145449383/535b2964-2e02-41ad-9120-5d1fc46866de)
![sorting 2](https://github.com/PREM3112/FindMaximum/assets/145449383/92b87b4a-2338-44ce-9f3c-7bea14a15da0)
![sorting 3](https://github.com/PREM3112/FindMaximum/assets/145449383/2f1aca95-717e-422e-a850-2e9563fcf06f)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
