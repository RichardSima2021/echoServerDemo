Source code obtained from ICS 53 Fall 2023

run server and give it a port as a commandline argument, i.e
```
$ ./server 42069
```

open a new terminal window (top right hand side + sign if you're on VS Code)

test server with telnet, use localhost (127.0.0.1) as hostname and the port you just used:
```
$ telnet 127.0.0.1 42069
```

run client with same localhost and port as cmdln arguments
```
./client 127.0.0.1 42069
```
Client stops upon entering Ctrl + D

Stop server with Ctrl + C


MAKE SURE YOU'RE ON THE SAME CIRCINUS MACHINE\
IF YOU SSH ONTO OPENLAB TWICE IN TWO DIFFERENT COMMAND PROMPTS YOURE PROBABLY GONNA END UP ON TWO DIFFERENT MACHINES\
IN THAT CASE LOCALHOST AINT GONNA WORK GOOD
