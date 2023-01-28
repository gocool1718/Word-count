# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Decleare number of words is 0

### Step 2: open it with txt file
 
### Step 3: Give range for i

### Step 4: Then nxt split the words 

### Step 5: count the number of words

### Step 6: Giving print statement for getting output

## PROGRAM:
```
Developed by: GOKUL S
Reference number: 22008488
'''
num_words=0
with open('wc.txt','r') as f1:         
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in a file = {}".format(num_words))
```

### OUTPUT:


![word count](https://user-images.githubusercontent.com/121148715/215275544-4b68c7e6-ec70-448a-87b5-9867df98355c.png)


## RESULT:
Thus the program is written to find the word count from a text.
