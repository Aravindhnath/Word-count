# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open visual studio code or jupyter lab.
### Step 2: 
Create file with .py extension. 
### Step 3: 
Also create .txt file and input sentences.
### Step 4:  
Write the code.
### Step 5: 
Run the program.
### Step 6: 
Print the values and end the program.

## PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : Aravindhnath T R
## REFERENCE NO : 22009024
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```

### OUTPUT:
![Count of words](https://user-images.githubusercontent.com/118790841/214718555-82725b9d-4b60-46b2-be11-546b756d7990.jpg)

![no of words](https://user-images.githubusercontent.com/118790841/214790919-4d565bd7-9a0b-41c6-a8a6-c8b5d975ca19.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
