# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Open the file in read mode and handle it in text mode

Step 2:
Read the text using read() function.

Step 3:
Split the text using space separator .we assume that words in a sentence are separated by a space character.

Step 4:
The length of the split list should equal the numbe of words in the text file.

Step 5:
You can refine the count by clearing the string prior t splitting or validatting the words after splitting
## PROGRAM:
```
'''
Program for getting the word count from a text.
developed by : marella dharanesh
Register Number: 22000785
'''
num=0
with open("git.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![WhatsApp Image 2023-01-24 at 18 56 02](https://user-images.githubusercontent.com/118707669/214307057-e19824c0-7e5e-4309-a409-bbd799049fd7.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
