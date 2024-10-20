1)The path variable
: Cleared the PATH variable so that rm cannot be found. PATH variable is where all the executables are stored. So, if the rm command is not found, the flag file cannot be removed.

![image](https://github.com/user-attachments/assets/32794232-b7a0-431a-b1cd-c3fd87ab1767)

2)Setting path
: Here, we added the /challenge/more_commands directory to PATH to expose the win program to be launched using its bare name.

![image](https://github.com/user-attachments/assets/4efd246c-37f7-4df7-97b0-909d9dbd0b3c)

3)Adding commands
: Redirected the contents of /flag to win. Made win executable. Read the contents of PATH variable. Updated the PATH variable to include the directory where win is located. Execute /challenge/run

![image](https://github.com/user-attachments/assets/f3beb4e9-f21c-40ed-b223-7f66545142bf)

4)Hijacking commands
: Redirected flag to rm. Used the absolute path of cat because PATH has been reset later. Made rm executable. Changed the path to /home/hacker Called /challenge/run.

![Uploading image.png…]()


