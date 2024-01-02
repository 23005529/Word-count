# Word-count
NAME : ALIYA SHEEMA 

REFERENCE NUMBER : 23005529

DEPARTMENT : AIDS
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
Harware - PCs

Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file

### Step 2: 
Open the required file by using the function "with".

### Step 3: 
Then use the laptop to assign the i value in the file.

### Step 4:  
Using split function to spilt the words

### Step 5: 
Finding the given length of the words by using len() fuction.

### Step 6: 
Calling the function and Printing the number of words.

## PROGRAM:
DEVELOPED BY : ALIYA SHEEMA
REFERENCE NUMBER : 23005529

num=0
with open("aliya.txt","r")as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)

### OUTPUT:
![Screenshot 2024-01-02 143459](https://github.com/23005529/Word-count/assets/139842207/4224e83c-9a8b-46b0-9901-2d52e11fdd71)

## RESULT:
Thus the program is written to find the word count from a text.
