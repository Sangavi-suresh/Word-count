# Word-count

## AIM:

To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED:

PC
Anaconda - Python 3.7

## ALGORITHM: 

### step1:

Create a txt file to count the number of word in that file.

### step2:

Open the txt file in read mode using open().

### step3:

Using split() function to split the words in the txt file and count it.

### step4:

Save the python program using .py extention.

### step5:

Run the python program in terminal to get the output.

### step6:

Number of words in the txt file is displayed as the output.

### program :
``` python
Reference no : 22008216
Developed by : sangavi s

num_words =0
with open('words.py','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={0}".format(num_words))
```

### OUTPUT:

![](./word.png)
![](./word1.png)

## RESULT:

Thus the program is written to find the word count from a text.
