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

7)Position thy self
: we run the /challenge/run command to find the path to the directory then we cd to the given directory then run the /challenge/run command to obtain the flag

![image](https://github.com/user-attachments/assets/4e6c8c34-25d7-4bf4-8d77-5771f1560de7)

8)Position elsewhere
: we use command /challenge/run to obtain the path to the directory then use cd to change directory to the given directory then use /challenge/run again to obtain the flag

![image](https://github.com/user-attachments/assets/e4901ca8-4102-4409-8b4b-96d0caa1720a)

9)Position yet elsewhere
: same as above

![image](https://github.com/user-attachments/assets/4cd6da89-fffb-48ee-96e1-3342f3145961)








