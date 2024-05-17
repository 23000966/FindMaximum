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
#developed by:santhosh kumar R
#register number:212223240153

def max_marks(array):
    array.sort()
    return array[-1]

```

ii)	# To find the maximum marks using the list method max().
```
#developed by:santhosh kumar R
#register number:212223240153

def max_marks(array):
    return max(array)



```

iii) # To find the maximum marks without using builtin functions.
```
#developed by:santhosh kumar R
#register number:212223240153

def max_marks(array):
    max1=array[0]
    for i in range(1,len(array)):
        if max1<array[i]:
            max1=array[i]
    return max1

```



## Output:
![image](https://github.com/23000966/FindMaximum/assets/153983364/fb8186fd-236a-4ee9-ba2f-f861251c6d12)
![image](https://github.com/23000966/FindMaximum/assets/153983364/d6e3d746-2261-48d7-813b-4df789ab9b71)
![image](https://github.com/23000966/FindMaximum/assets/153983364/9eadcd7c-fd4d-4c23-8194-c898edc1c3af)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
