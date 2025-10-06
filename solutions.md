## Exercise 1
### What is the difference between 'cat' and 'touch' commands.
  Answer: cat is use to display the content of a file, while touch is used to create an empty file or update the timestamp of an existing file.

### Create a file using the 'cat'  and the 'touch' commands.
![Cat](images/create_file_with_cat.png)
![Touch](images/create_file_with_touch.png)

## Exercise 2
### What is file permissions in linux and what are the various ways of displaying the file permissions in linux.
    File permissions in Linux determine who can read, write, or execute a file. They are represented by a combination of letters and symbols that indicate the access level for the owner, group, and others
    - Using the `ls -l` command to list files with detailed information, including permissions.
    - Using the `stat` command to display detailed information about a file, including its permissions.

### What is the default `permissions` given to a file when its created.
    rw-r--r-- (read and write for the owner, read-only for the group and others)

### What is the default `permissions` given to a folder when its created.
    rwxr-xr-x (read, write, and execute for the owner, read and execute for the group and others)

### How do you create `a folder` in linux.
    mkdir foldername


## Exercise 3
### Firstly, research and find the command used to print the number of lines, words and characters in a file.
    wc (word count)

### Secondly, apply the command to the `animals.txt` file attached to this exercises.
![word count](images/wc.png)


## Exercise 4
### Using a `linux command`, get the first 3 lines in the `animals.txt`
![head command](images/first_3_lines.png)

### In addition to getting the first 3 lines, count only the words within this range.🫣
![head and wc command](images/first3_and_wc.png)


## Exercise 5
### There is a command in linux that starts with `g`, that has the capability to search through fiiles. What is the `command`?
    grep

### Using this command, search for the words, `Nutshell`, `Perl` and `Dansoman` in `animals.txt`
![grep command](images/grep_search.png)


## Exercise 6
### What `command` is used to list all files in a directory?
    ls
### Wait a minute....what is a `directory` in linux 😅?
     A directory is a folder that contains files and other directories, or it's a type of file that stores references to
    other file. It is used to organize and manage files on a computer system.

## Exercise 7
### What is the `pwd` command what does it do?
    The `pwd` (print working directory) is used to display the current directory you are in within the terminal.
![pwd command](images/pwd_command.png)
### What is the difference between `echo` and `cd` command?
    The `echo` command is used to display a line of text or a variable value in the terminal, while the `cd` (change directory)
    command is used to change the current working directory to a specified directory.
![echo and cd](images/echo_cd.png)


## Exercise 8
### What is the `dirs` command in linux and what does it do?
    The `dirs` command in Linux is used to display the list of directories in the directory stack.
### I need to find out what the command `mv` does, what command do I need to use to find out more about the `mv` command in linux.
    You can use the `man mv` command to find out more about the `mv` command in Linux.
![man](images/man_mv.png)


## Exercise 9
### Using the `date` command, print out the current day in the terminal.
![date command](images/date_command.png)
### What is the difference between `awk` and `grep` commands? Please provide examples.
    The `grep` command is used to search for specific patterns or strings within a file or input, while the `awk` command is a powerful text processing tool that can perform complex operations on data, such as filtering, transforming, and formatting.

Example of `grep`:

![grep example](images/grep_search.png)
    Example of `awk`:
![awk example](images/awk.png)


 ## Exercise 10
### What are environment variables? List out 5 env variables(There is a command to list them out in your terminal.😜)
    Environment variables are dynamic values that can affect the way the computer runs. They are used to store configuration settings and other information that can be accessed by programs and scripts.

    Five common environment variables are:
    1. PATH: Specifies the directories where executable files are located.
    2. HOME: Represents the current user's home directory.
    3. USER: Contains the username of the current user.
    4. SHELL: Indicates the default shell for the user.
    5. LANG: Defines the language and locale settings for the system.


### What is the difference between `more` and `less` commands.
    The `more` command is used to view the contents of a file one screen at a time. However, it has limited navigation 
    capabilities and only allows forward movement while The `less` command is a more advanced pager that also allows
    you to view the contents of a file one screen at a time, but it provides more navigation options. With `less`, 
    you can scroll both forward and backward through the file, search for specific text, and navigate using various commands.


## Exercise 11
### There is a command in linux for seeing a type of a file in a directory what command is that?
![file command](images/file_command.png)


## Exercise 12
### The Unix system has a filesystem tree what is it called and list 3 important folders in this tree.
    Root filesystem tree
    1. /bin: Contains essential binary executables for system operation.
    2. /etc: Contains system configuration files.
    3. /home: Contains user home directories.


## Exercise 13
### In unix are 2 commands `head` and `tail`. Kindly illustrate how this is used in the git bas terminal.
    The `head` command is used to display the first few lines of a file, while the `tail` command is used to display the last few lines of a file.
![head and tail](images/head_tail.png)


## Exercise 14
### Create a file called students.txt with the following content:
  ```
    John Doe,Computer Science,3.8
    Jane Smith,Mathematics,3.9
    Bob Johnson,Physics,3.7
    Alice Brown,Computer Science,3.6
  ```
NB: add screenshots for solutions to the ff questions
- ✅ Display the entire contents of the file
- ✅ Display only the first 2 lines
- ✅ Display only the last 2 lines
- ✅ Count the number of lines, words, and characters in the file
- ✅ Search for all lines containing "Computer Science"
- ✅ Create a new file with only the Computer Science students
- ✅ Sort the file by GPA (last column)
- ✅ Replace all occurrences of "Computer Science" with "CS" and check the final output.

![Exercise 14](images/exercise14ScreenShot.png)



## Exercise 15
### Create a log file called server.log with this content:
  ```
    2023-01-15 10:30:25 INFO User login successful
    2023-01-15 10:31:15 ERROR Database connection failed
    2023-01-15 10:32:10 INFO User logout
    2023-01-15 10:33:45 WARNING Low disk space
    2023-01-15 10:34:20 ERROR Authentication failed
    2023-01-15 10:35:05 INFO System backup completed
  ```
  NB: add screenshots for solutions to the ff questions
### Find all ERROR entries
![Find ERROR](images/error.png)
### Count how many WARNING entries exist
![Count WARNING](images/num_warning.png)
### Extract all timestamps (first two columns)
![Extract timestamps](images/timestamps.png)
### Find lines that contain either "login" or "logout"
![Find login or logout](images/login_logout.png)
