1)Redirecting output
: we write the text PWN into a file COLLEGE using the command echo PWN > COLLEGE 

![image](https://github.com/user-attachments/assets/dc0017ee-8d6e-438b-ae0f-a3c8d76e4cd3)

2) Redirecting more output
: we redirect the output of the /challenge/run to the myflag file using the command /challenge/run > myflag and use cat myflag to obtain the flag

![image](https://github.com/user-attachments/assets/00ad115f-d076-4463-9d6a-38fffdb163cd)
![image](https://github.com/user-attachments/assets/5ac0ba0d-89a2-4b8e-bf36-1c1e43798efa)

3)Appending output
: first we redirect the first half of the output of /challenge/run to the file /home/hacker/the-flag then append the second half below it which completes the /challenge/run file
and we use cat /home/hacker/my-flag to obtain the flag

![image](https://github.com/user-attachments/assets/3caf8abc-2414-4f61-9976-307a36f41a8e)

the above code redirects the first half

![image](https://github.com/user-attachments/assets/f7062bbf-03cf-4df4-92c8-dba9ba88757a)

the above code appends the second half


4)Redirecting errors
: errors can be redirected to separate files by using 2> which redirects the output error to another file, here we redirect the output of /challenge/run to myflag and the errors to 
another file called instructions using the command /challenge/run > myflag 2> instructions

pwn.college{M2yopphakLVcCdfqN34pFHoykKj.ddjN1QDLwITM1czW}

5)Redirecting input
: in this challenge we redirect the the text COLLEGE into a file called PWN which is in turn redirected to the file /challenge/run

![image](https://github.com/user-attachments/assets/935b7f6f-fbce-4116-becb-94b897e37035)

6)Grepping stored results
: we redirec the contents of the file /challenge/run to the file /tmp/data.txt and grep the flag by using the command grep 'pwn' /tmp/data.txt 

![image](https://github.com/user-attachments/assets/ef3b10c7-1d58-4af3-9e12-f979272ce19a)

![image](https://github.com/user-attachments/assets/dcd2e961-1a6f-4d0b-85fe-6cded7dd2bfd)

7)Grepping live output
: we directly grep the flag from the /challenge/run file instead of redirecting it to a seperate file

![image](https://github.com/user-attachments/assets/ec7ac525-250f-486e-ac7b-4e84f4337411)

8)Grepping errors
: we use the command /challenge/run 2>&1 | grep "pwn" , the 2>&1 redirects standard error to standard output and the grep 'pwn' locates texts containing the text 'pwn'

![image](https://github.com/user-attachments/assets/e0dcf361-c577-43f1-941b-b13c62f00a8f)

9)Writing to multiple programs
/challenge/hack runs and produces output.
tee duplicates the output, sending one copy to the process substitution >( /challenge/the ), which sends the output to /challenge/the.
The second copy of the output is piped to /challenge/planet.
/challenge/hack | tee >( /challenge/the ) | /challenge/planet

![image](https://github.com/user-attachments/assets/3109670e-4ddc-4162-8932-7585984c0926)

10)Split piping stderr and stdout
: 1> redirects standard output (stdout) to /challenge/planet.
2> redirects standard error (stderr) to /challenge/the.
The >( ) syntax allows for process substitution, directing the output to another program.

![image](https://github.com/user-attachments/assets/f986e228-4018-4bb3-b557-40e951411c78)















