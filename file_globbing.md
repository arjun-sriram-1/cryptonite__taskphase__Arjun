1)Matching with *
: here we use globbing to run the cd command and give the argument to it as /ch* as less than 4 characters can only be used to cd into the challenge file

![image](https://github.com/user-attachments/assets/c628dda8-1360-4736-9897-c89a56487b86)
![image](https://github.com/user-attachments/assets/5f1915de-c112-4978-b946-aa7185839ab7)

2)Matching with ?
: the ? character is used for filling in single characters in a word.. here the cd command is run with the argument as /?ha??enge where any character can be present in the place of ?

![image](https://github.com/user-attachments/assets/6f35690a-adff-41fc-8db9-09dacfefa313)

3)Matching with []
: [] is used to locate a subset of potential characters, here the /challenge/run is used with file_[bash] as an argument to find the flag

![image](https://github.com/user-attachments/assets/50e4bf62-adf1-40ce-bb04-24b2dab83a0e)

4)Matching paths with []
: we can use [] from the absolute path also, here the /challenge/run command is run with /challenge/files/file_[bash] to find the flag

![image](https://github.com/user-attachments/assets/80d4b668-92b7-4e46-95d5-821ac566e148)

5)Exclusionary globbing
: we use a mixture of globbing commands to filter out files by using ! before entering the characters in the [], here we cd into the /challenge/files then we use /challenge/run [!pwn]* to
find files which do not start with the letter p w or n

![image](https://github.com/user-attachments/assets/1d48744f-10d0-4cd6-91b3-9c992b74c916)

6)Mixing globs
: cd into the /challenge/files and then use /challenge/run [cep]* to find the flag

![image](https://github.com/user-attachments/assets/e7146265-6285-46ec-bded-91c0050a6410)











