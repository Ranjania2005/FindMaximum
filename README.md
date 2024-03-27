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

def max_marks(a):
    a.sort()
    result=a[-1]
    return result

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(a):
    res=max(a)
    return res


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(a):
    res=0
    for i in a:
        if i>res:
            res=i
    return res
        


```



## Output:


![Screenshot (189)](https://github.com/Ranjania2005/FindMaximum/assets/151624950/3c1a6b40-9ef4-4e83-80b7-6d1c4925ba2d)
![Screenshot (189)](https://github.com/Ranjania2005/FindMaximum/assets/151624950/8194b61e-c1be-405e-a5f7-ae6f74d7e015)
![Screenshot (189)](https://github.com/Ranjania2005/FindMaximum/assets/151624950/5bdbbbb7-0c25-4190-8533-6abd31b70462)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
