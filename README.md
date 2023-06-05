# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a new file.

## Step 2:
Open the both the files using the function"with".

## Step 3:
Open the first file created in read mode.

## Step 4:
Open the second file created in append mode.

## Step 5:
Then use for loop.

## Step 6:
Calling the function to copy the contents fron file one to file two.

## PROGRAM:
Program to copy one contents from one file to another

#Developed by:Narendran .B

#Register no:212222240069

```
with open('nachi.txt','r') as f9:
    with open('zia.txt','a') as f8:
        for line in f9:
            f8.write(line)
```

### OUTPUT:
![image](https://github.com/naren2704/copy-file/assets/118706984/1314adf4-223f-48b9-9214-3bb6fae6c31f)




## RESULT:
Thus the program is written to copy the contents from one file to another file..
