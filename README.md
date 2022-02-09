# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file with some written information

### Step 2: 
Open the text file with open()
 
### Step 3: 
Open the empty text file to copy the information

### Step 4:  
By using the function write() copy the text written in the file1 to file2

### Step 5: 
End the program
  

## PROGRAM:
with open("file.txt") as fp:
     with open("file2.txt","w") as fp1:
         line=fp.read()
         fp1.write(line)

### OUTPUT:
![image](https://user-images.githubusercontent.com/94174536/153131220-50f8a894-ed16-4e84-8e02-4fca346634fb.png)
![image](https://user-images.githubusercontent.com/94174536/153131273-f597d733-999b-4ec3-a51f-c97e28c76f16.png)
![image](https://user-images.githubusercontent.com/94174536/153131314-99934933-73ed-44e6-9a6a-00b99954b6c7.png)
![image](https://user-images.githubusercontent.com/94174536/153131352-ff5992b9-ff98-4f4c-a99c-e115ce969339.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
