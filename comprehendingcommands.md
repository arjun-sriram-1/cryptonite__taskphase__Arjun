1)Cat not the pet but the command
:the flag file is read with cat command
![image](https://github.com/user-attachments/assets/7c3f4177-bf09-451e-a70d-70be1ada8e7b)

2)Catting absolute paths
:the flag file is read with the cat command but the absolute path of the file is given as the argument
![image](https://github.com/user-attachments/assets/72684e33-f1fb-426b-8e1f-be74e925a221)

3)More catting practice
:the flag is hidden in a file and is retrieved by giviing the argument of the cat command as the absolute path of the flag file

![image](https://github.com/user-attachments/assets/3f8dcd03-3d39-45d1-bded-9d8bbfb6c2aa)

4)Grepping for a needle in a haystack
:the flag is hidden in a huge file, so the test containing pwn.college is grepped out by giving the below command to find the flag as the flag always starts with 'pwn.college'
![image](https://github.com/user-attachments/assets/bc6132d5-6eb6-4cb1-822a-7da66dfb7fda)

5)Touching files
:we cd into the tmp folder and create two files pwn and college using the touch command and then use /challenge/run command to collect the flag

![image](https://github.com/user-attachments/assets/63f110a5-a7bb-49fe-a9e1-bdf0873e0bee)

6)Removing files
:a file named delete_me is deleted using the rm command and the file name which is delete_me as the argument and /challenge/check is used to collect the flag

![image](https://github.com/user-attachments/assets/30f45aa4-91c2-4d2f-b5c0-7875f12c776b)

7)Hidden files
:files that start with . are hidden, and ls does not show the file containing it, so the ls -a command is used to show all the files containing . at the beginning and the file containing the flag is found and the cat command is used to open the file and capture the flag

![image](https://github.com/user-attachments/assets/a33e3338-409e-4cc9-9cbe-6653de37a3fb)

8)Making directories
:here we create a directory /tmp/pwn by using the mkdir command and create a file in it and use the /challenge/run command to get the flag

![image](https://github.com/user-attachments/assets/7c565432-a97e-4b9b-bd81-f7525eddbe2c)
![image](https://github.com/user-attachments/assets/f2b23ebd-2f5c-4ecc-bd18-025dc365826b)

9)Listing files
: we use the command ls /challenge to list the files in the in directory challenge to find the renamed file and then use its absolute path to obtain the flag

![image](https://github.com/user-attachments/assets/5cb3e9a1-eb18-44f1-b221-8110d7dcc73b)

10)An epic filesystem quest


![image](https://github.com/user-attachments/assets/261aa037-dfa7-4df9-877b-086660d16b3a)

![image](https://github.com/user-attachments/assets/f2b98dbd-58a2-4f88-b164-aeb4be2a066f)

![image](https://github.com/user-attachments/assets/294be134-5042-4a5b-9d0b-5117f5a37233)

![image](https://github.com/user-attachments/assets/a63f2a73-f4f9-46a3-8bf2-d51fc48a6c07)

11)linking files
: 














