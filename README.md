# DevOps-Basic-commands-
Basic commands 

### 1.  **File Management:** Practice creating (`touch`), copying (`cp`), moving/renaming (`mv`), and deleting (`rm`, `rm -i`, `rm -r`) files and directories. View and search contents using `cat`, `less`, `head`, `tail`, `find`, and `grep`.

### Creating ,moving, copying and removing files  using touch, mv and cp commands 

I created a directory using <mkdir> command The director name craeted was Directory2 which i have worked with for this 

first part of the project . I < cd > into Directory2 and created a file using the < touch >command. the files created were 

file.txt2 as well as file.txt1 and file.txt3 .txt indicating a file name .. I used the command <ls -l > to check the files 

has been created and it permissions as well.As i had the right to write the file , i  used the command < nano > to write 

some text into the file . I used ctl+x,y enter to save the edited file . Now that some text had been created in the file 

.txt2,i used <cat > command to check the content of the file  and the content which had been writen in the file.txt1 using 

the nano editor was reflected as text.


I then used the < cp > command the copy the content of file.txt1 to file.txt2. I confirmed that the file.txt1 has been 

copied to file.txt2 by using a  <cat > command  to see the content of file.txt2. The content of the file had been copied 

into the file . And both files appered when i checcked their existence using the command < ls >.


I  then decided to used the<mv> command . these command is used to move files into other files or other directories . I 

moved the file.txt2 and its content to file.txt3. To confirm this i used the  <cat > command with the file file.txt3 and 

the content from file.txt2 had been copied into the file.txt3 and when i checked the list of the files in the Directory2, 

file.txt2 was missing as it had been moved into file.txt3.

<rm > command is used to remove files from a directory . I created a few files using the < touch >command  and created 

rmtest1.txt, rmtest2.txt and rmtest3.txt. I then used the <rm -i >which is an interactive command and removed rmtest3.txt. 

I got a prompt to ask if i wanted to deleted the file .My answer was "yes". the file was deleted from the directory . When 

i checked the file using the ls command ,it was missing from the directory.

All these commands have been demonstrated below with the use of a photo attached .

<img width="642" height="917" alt="image" src="https://github.com/user-attachments/assets/008d80d3-3560-428a-95ae-d3a3e7202b76" />


## Working with cat, less ,find, head, tail commands

The image below shows how the commands above have been used . I will go throught eh commands 1 by 1  explaining how they 

have been used 

<img width="570" height="532" alt="image" src="https://github.com/user-attachments/assets/b321a474-ece2-404d-960e-
   f0041d820c69" />


The < cat > command is used to check the contents of a file . The command i used here to check the file content of the 

file.txt1. The less command is used to check the contentof a big file and show less or no content of the file depending on 

the size of the file. These command has been used in the file.txt1 and it didnt  show any content as the file is a small 

file . The next command we aren going to look at as i used in the project  is the < head > command . The  command is used 

to to check the content  at the top of the file  and the opposite command  is the < tail> command which is used to theck 

the end of a vig file . I helps ypu be able to get to the bottom of the file with ease without having to scroll down the  

whole file .All theabove commands are used and accompanied bythe file name . for example  <cat filename>, <less filename 
                                                                                                             >, <head 
filename> and <tail filename>

Lastly we look at the find command  which is also used in combination with the file name for example <find 

filename/directory name >.These has been demonstrated by  trying to find the Directory2 which was a success.


   ## Working with Grep command 

   Grep command is used to find  and match text patterns in files .

    These has been demonstrated below. < grep command has been used toexplore the file content of the file.txt1.The 
    
    command has been seen being used to find the word hello in the file .txt1. The command used id grep 'hello' file.txt1. 
    
    The word hello has been highlighted  in red as a result from the command .
   
     < grep -r 'i' filename.txt1>  these has demonstrated that the letter 'i' has been highlighted through out file. The 
     
     command <grep --colour 'Thursday'. These has been demonstrated by highlighted the word Thursday in the file.
     
     The <grep command with the tag -c > is used to cound the number of times a word has bbeen used in a file . For 
     
     instance in this project, it has been used to find the sentence  "looking forward to Thursday" thes is not found 
     
     anywhere in the file and the feedback was 0 and when the same command was used to check for the word " thursaday" an 
     
     output of 1 was shown meaning the word Thursady has been found in the file.txt1  once which is true .

     See the attached immage for demonstartion#
     
   <img width="585" height="662" alt="image" src="https://github.com/user-attachments/assets/fc45d8f1-7462-424c-960e-b8fef8b157dd" />

### 2.  **Directory Navigation:** Navigate the file system using `pwd` and `cd` (absolute vs. relative paths). Create nested structures with `mkdir -p` and explore standard directories like `/etc`, `/var`, and `/tmp`.

## Working with pwd Command to get an absolute path

The next command <pwd> command is an absolute command that show you where you are at the moment on your terminal using / on the path.
cd takes you  to the file or directory you want to be in . These is demontarate d by rhe command <cd directoryname./file name as demonstrated in the photo below.
<mkdir -p> is usedd to create a parent directory. The parent directory has the files /etc/, /var ,/tmp are used when troubleshooting .

<img width="375" height="92" alt="image" src="https://github.com/user-attachments/assets/600dd186-a743-448a-95f5-3b4f31f4d873" />

Playing around with cd command and ls to explore etc, tmp and var files

<img width="745" height="841" alt="image" src="https://github.com/user-attachments/assets/faa6e6da-eac3-4006-94b1-ca1c7a344328" />

### 3.  **System Monitoring and Administration:** Inspect system health using `ps aux`, `top`, `df -h`, `free -m`, and `uptime`. Manage users/groups and configure file permissions and ownership using `chmod`, `chown`, and `sudo`.

## ps,top df-h  and free-m commands are shown in this images 


<img width="587" height="897" alt="image" src="https://github.com/user-attachments/assets/ebb62c77-c13e-4e03-a22f-08651346c528" />

<img width="550" height="247" alt="image" src="https://github.com/user-attachments/assets/1272d4d5-02d0-4744-9ef0-0e33e852e641" />
The commands demonstrated above  can be called the monitoring commands.

< ps> is used to display the information about processes one is working on on the terminal.

< free > the memory which is being utilized by the system. With a -h it shows these in human redable state. The <top > 

command is ussed to show more details and the work happening in the system one is working on.

### .  **Networking Basics:** Verify connectivity and network configuration using `ping`, `ip addr`, and `netstat` or `ss`.

To check connectivity we csn use <ping> command with thenextension using a certain website to test connetivity for 

eaxample used here  is google.com as "ping -c google.com" command  and it bringa the output showing the IP address of 

google.com <df -h> shows the amout of memoery across linux system.The < free > command is used to show the amout of 

Memeory in linux systems.

<img width="932" height="862" alt="image" src="https://github.com/user-attachments/assets/f736ed70-e98d-4818-99fb-bbba77daa8c7" />


### 5.  **Pipes and Redirection:** Practice redirecting output (`>`, `>>`) and errors (`2>`). Chain commands together using pipes (`|`) to filter and process data (e.g., `grep`, `awk`, `sort`, `uniq`).

## Pipe commands

The above commands above have been demonstrated above.

As demonstared above the < awk > command has been demonstrated . The cpmmand in combination with other commands is used to 

give a feedback of the command . Hre it has been given the task to print the content of the file.txt1 <awk '{print}' 

file.txt1 > . The content of the file has then been printed out below these command.

grep has also been used here as well  to demonstare the presence of Apache among the files in the system that has been set 

up < ps aux|grep apache

 The command  <uniq u filename >is used to  open a file and <uniq -f filename > is used to create a formula in a file . 
 
 For instance in this enviroment the file file.txt1 has been edited using the nano editor and the days of the week have 
 
 been added not in order. When cthe command < uniq -f> command the days of the weekare arrangedin order as per theit 
 
 numbers.
 
    # See the photo below
 
 <img width="762" height="850" alt="image" src="https://github.com/user-attachments/assets/77a56fbd-3fce-4e23-b343-c3cf6acae284" />

### 6.  **Shell Scripting:** Write a reusable Bash script that incorporates variables, conditionals, and loops to automate a directory creation and logging task. Ensure the script is executable.

A reusable Bash script is demonstrated below with permissions needed . Had a bit of a challange not knowing how to create a bash file 

<img width="805" height="717" alt="image" src="https://github.com/user-attachments/assets/a39edb2b-d9e9-47f7-b99c-34c73d57588e" />

<img width="726" height="437" alt="image" src="https://github.com/user-attachments/assets/3a2fa5a0-54d8-47a5-936c-9fad78df8c74" />






