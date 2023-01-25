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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: M Srinath
RegisterNumber: 22000990
'''
def max_marks(marks):
    large=max(marks)
    return large


```

ii)	# To find the maximum marks using the list method max().
```''' 
Program to find the maximum marks using the list method max().
Developed by: M Srinath
RegisterNumber: 22000990
'''
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```''' 
Program to the maximum marks without using builtin functions.
Developed by: M Srinath
RegisterNumber: 22000990
'''
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
![Screenshot from 2023-01-25 22-44-33](https://user-images.githubusercontent.com/118678482/214633862-ccfc30d7-97ab-4f6b-9fa5-3b1b11aeb0b9.png)

![Screenshot from 2023-01-25 22-44-33](https://user-images.githubusercontent.com/118678482/214634270-bc3d23cb-8d0d-4e27-b41e-11489323aecf.png)


![Screenshot from 2023-01-25 22-44-33](https://user-images.githubusercontent.com/118678482/214634333-1bf54db3-c204-4239-88d7-4f735cd98913.png)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
