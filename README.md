# Find-Files-With-Linux-Commands

<h2>Activity overview</h2>

Previously, I learned about Linux and how to communicate with the OS through the shell. I also learned how to use some of the core commands to navigate the Linux file system and read content from files it contains.

These are essential skills. For example, when investigating unauthorized access, I might navigate to and then read a user access report.

In this lab activity, I’ll navigate a Linux file structure, locate files, and read the contents of files. 

As a security analyst, it’s key that I know how to navigate, manage, and analyze files remotely via a Linux shell without a graphical user interface.

<h2>Scenario</h2>

In this scenario, I have to locate and analyze the information of certain files located in the ```/home/analyst``` directory.

Here’s how I’ll do this: First, I’ll get the information of the current working directory and display the contents of the directory. Second, I’ll navigate to the ```reports``` directory and list the subdirectories it contains. Third, I’ll navigate to the ```users``` subdirectory and display the contents of the ```Q1_added_users.txt``` file. Finally, I’ll navigate to the ```logs``` directory and display the first 10 lines of a file it contains.

<h2>Task 1. Get The Current Directory Information</h2>

In this task, I must use the commands I learned about to check the current working directory and list its contents.

1. Display the working directory.
   
2. Display the names of the files and directories in the current working directory.
   
Here, I can see the current working directory:

[image]

I can see that the current working directory contains [] directories:

[image]

<h2>Task 2. Change Directory and List the Subdirectories</h2>

In this task, I must navigate to a new directory and determine the subdirectories it contains.

1. Navigate to the ```/home/analyst/reports``` directory.

2. Display the files and subdirectories in the ```/home/analyst/reports``` directory.

Here, I can see the name of the subdirectory in the ```/home/analyst/reports``` directory:

[image]

<h2>Task 3. Locate and Read the Contents of a File</h2>

In this task, I must navigate to a subdirectory and read the contents of a file it contains.

1. Navigate to the ```/home/analyst/reports/users``` directory.

2. List the files in the current directory.

3. Display the contents of the ```Q1_added_users.txt``` file.

Here, I can see that the employee with the username “aezra” works in the [] department:

[image]

Here, I can see the employee_id of the user “mreed” in the Information Technology department:

[image]

<h2>Task 4. Navigate to a Directory and Locate a File</h2>

In this task, I must navigate to a new directory, locate a file, and examine the contents of the file.

1. Navigate to the ```/home/analyst/logs``` directory.

2. Display the name of the file it contains.

3. Display the first 10 lines of this file.

Here, I can see that there are [] warning messages in the first 10 lines of the ```server_logs.txt``` file:

[image]

<h2>Conclusion</h2>

I now have practical experience in using basic Linux Bash shell commands to

- navigate directory structures with the ```cd``` command,
- display the current working directory with the ```pwd``` command,
- list the contents of a directory with the ```ls``` command, and
- display the contents of files with the ```cat``` and ```head``` commands.

Navigating through directories and reading file contents are fundamental skills that I’ll often use when communicating through the shell.
