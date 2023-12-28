# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
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
```
#Program to find the word count.
#Developed by: MARXIN LIJO M
#RegisterNumber: 23013468
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("total number of words:",count)
program() 
```
### OUTPUT:
![Screenshot 2023-12-25 125643](https://github.com/MARXINLIJO/Word-count/assets/145742540/2422a586-48ca-4bb4-b5ea-c3e05c392738)

![Screenshot 2023-12-25 125706](https://github.com/MARXINLIJO/Word-count/assets/145742540/74e53fbc-cf8c-4064-afc2-e6920b9c92f7)
![Screenshot 2023-12-25 125633](https://github.com/MARXINLIJO/Word-count/assets/145742540/b88c5773-c245-404b-b8ff-f9f54d33c945)



## RESULT:
Thus the program is written to find the word count from a text.
