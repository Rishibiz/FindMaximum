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

#program developed by : RISHI CHANDRAN R
#roll num:212223043005
def max_marks(a):
    a.sort()
    return a[9]

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(a):
    return max(a)


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(a):
    max =a[0]
    for i in a:
        if(i>max):
            max=i
    return max
        
    


```



## Output:
<img width="1468" height="857" alt="Screenshot 2025-11-21 090333" src="https://github.com/user-attachments/assets/8cd13eef-5b3f-462a-a5a8-1d71503aafd4" />

<img width="1012" height="849" alt="Screenshot 2025-11-21 090346" src="https://github.com/user-attachments/assets/bf1c44c1-3a5d-4f0a-b4f7-682f5e062b42" />

<img width="1012" height="849" alt="Screenshot 2025-11-21 090346" src="https://github.com/user-attachments/assets/c88778de-38a1-4d3a-abe8-5272c2051637" />


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
