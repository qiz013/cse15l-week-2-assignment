## Step1: 

![image](screenshot1.png)
- install the vscode from the website
- get started

## Step2:

![image](screenshot2.png)
- log in to my CSE15L account on ieng6
- need to change passward for the first log-in to activate the account

## Step3:

![image](screenshot3.png)
- command `ls` lists the contents of the current directory
- command `ls -lat` lists the contents, including the hidden files in the long format

## Step4:

![image](screenshot4.png)
- use command "scp" to move the c++ source file "hello.cpp" to my ieng6 account
- the file can be compiled and runned after being moved

## Step5:

![image](screenshot5.png)
- use command "ssh-keygen" creates a pair of files called the public key and private key stored in the server and client respectively

![image](screenshot5.png)
- but I get stuck when copying the public key to my account on the server. How to solve it?

## Step6:

![image](screenshot5.png)
- write a command in quotes at the end of an ssh command to directly run it on the remote server, then exit
- this should not require password if my problem in Step5 can be solved
