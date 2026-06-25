1. User and Group Verification

Command Used: id  

Output: uid=1000(coder) gid=1000(coder) groups=1000(coder),27(sudo)  

Explanation: I used the "id" command to get details about the username and id, the groups I belong to.

Screenshot: ![Q1 Image1](images/q11.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    
2. Current Shell

a) Command used: echo $SHELL  

Ouput: /bin/bash

Explanation: I used the echo $SHELL command to display the current shell being used. The $SHELL variable is an environment variable that stores the path to the user's default login shell, and the echo command prints the value of that variable to the terminal.

Screenshot: ![Q1 Image2](images/q12.png)  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------    

3. Current Working Directory

Commands used: pwd

Ouput: /home/coder

Explanation: I used the pwd command to display the current working directory. The command stands for "print working directory" and shows the absolute path from the root directory to my present location in the filesystem.

Screenshot: ![Q1 Image3](images/q13.png)  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4. List of files and working directories

Command used: ls -l

Output: A list of files and folders were generated.

Explanation: I used the ls -l command to list the files in the present directory. While ls is used to list files, the -l option lists more details about it, such as permissions, ownership, and modification timestamps.  

Screenshot: ![Q1 Image4](images/q14.png)  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

5. Network connectivity verification result

Command used: ping -c 4 www.google.com  

Ouput Screenshot: ![Q1 Image9](images/q15.png)  

Explanation: I used the ping to send packets to google.com. Since it would continuously send pings, I used the -c option to limit the number of pings to 4.  

