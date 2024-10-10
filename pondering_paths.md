1) The root
: we invoke the pwn program using its absolute path which is /pwn

![image](https://github.com/user-attachments/assets/483735ee-62b6-4977-b568-3d3cfb189d24)

2)Program and absolute paths
: we execute the run file which is in the challenge directory which is in the / directory with the command /challenge/run

![image](https://github.com/user-attachments/assets/a0017066-f6b5-4d10-811b-144e4f550f84)

3)implicit relative paths, from /
: we first navigate to the root directory using cd / and then run the challenge/run command to run it as the challenge states that the command must start with the letter 'c'

![image](https://github.com/user-attachments/assets/7fdb5cbd-c180-48e6-8198-6bca2da68837)

4)explicit relative paths, from /
: we first navigate to the root directory then use ./challenge/run were the . refers to the current directory

![image](https://github.com/user-attachments/assets/aaf80576-4860-435b-9bc1-52612aee7c2d)

5)implicit relative paths
: we first navigat eto the root directory using cd / then run then we cd into tho challenge directory then run the ./run to get the flag were the . refers to the current directory

![image](https://github.com/user-attachments/assets/38a64657-1022-487a-8349-2b82d2dd0510)

6)home sweet home
: the cd ~ command is run to navigate to the home directory then  /challenge/run ~/a which will write the flag to a file named a from which we can obtain the flag

![image](https://github.com/user-attachments/assets/cb47d00d-0da0-4c4b-91db-3b56eb18d8e2)





