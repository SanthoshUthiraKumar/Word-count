# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:
![CountWordOutput](https://user-images.githubusercontent.com/119477975/214090999-ac03eb50-3977-4c82-94a8-7d3afc4e786d.png)
![CountWordFile](https://user-images.githubusercontent.com/119477975/214091182-07b7320f-4fba-4908-8bbd-57ade5041ca1.png)

## RESULT:
Thus the program is written to find the word count from a text.
