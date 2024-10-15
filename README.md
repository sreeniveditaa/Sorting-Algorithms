# DATE:
# EXP 08 : Selection sort and Insertion sort
## Aim:
To write a program to perform selection sort and insertion sort using python programming.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Selection Sort Algorithm:
1.	Set the first unsorted element as the minimum
2.	For each of the unsorted elements, check if the element < current minimum.
3.	If yes, set the element as the new minimum.
4.	Swap minimum with first unsorted position.
5.	Repeat the steps 2 and 3 for all the elements in the array.
## Insertion Sort Algorithm:
1.	Set the first element as sorted element j.
2.	For each unsorted element X, check if current sorted element j >X.
3.	If yes, move sorted element to the right by 1.
4.	Break the loop and insert X.
5.	Repeat the steps 2 to 4 for sorting all the elements in the array.
## Program:
i)	#Selection Sort
```
#Write a program to sort the elements in the list using the Selection Sort algorithm.
#Deveolped by: SREE NIVEDITAA SARAVANAN
#Register no:212223230213
num=eval(input())
for i in range(len(num)):
    low=i
    for j in range(i+1,len(num)):
        if num[j]<num[low]:
            low=j
    num[i],num[low]=num[low],num[i]
print(num)

```
ii)	#Insertion Sort
```
#Write a program to sort the elements in the list using the Insertion Sort algorithm.
#Deveolped by: SREE NIVEDITAAA SARAVANAN
#Register no:212223230213
num=eval(input())
for i in range(1,len(num)):
    insert=num[i]
    j=i-1
    while j>=0 and num[j]>=insert:
        num[j+1]=num[j]
        j=j-1
    num[j+1]=insert
print(num)

```

## Output:

![Screenshot 2024-10-15 193127](https://github.com/user-attachments/assets/83bd1f03-6aac-4f49-b890-dce56667a568)

![Screenshot 2024-10-15 193138](https://github.com/user-attachments/assets/51deae40-6894-4597-9cfa-8d96a4a5b31a)

![Screenshot 2024-10-15 193154](https://github.com/user-attachments/assets/07e61f9b-6400-4de2-ab9a-e52702084f4b)

![Screenshot 2024-10-15 193210](https://github.com/user-attachments/assets/ac0f54a1-5743-4acf-acae-70723939f3af)


## Result:
Thus the program is written to perform selection sort and insertion sort using python programming.
