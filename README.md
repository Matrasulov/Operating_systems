# Operating_systems


## Week 3. 
## Lab work

## File management
```
ubuntuvm@ubuntuvm:~$ mkdir Videos/Watched  
ubuntuvm@ubuntuvm:~$ ls -R Videos
Videos:
Watched
Videos/Watched:
ubuntuvm@ubuntuvm:~$ cd Documents
ubuntuvm@ubuntuvm:~/Documents$ mkdir ProjectX Projecty
ubuntuvm@ubuntuvm:~/Documents$ ls
ProjectX Projecty
```

In following example, both files and directories are to be organized by creating a new directory using **mkdr** command
```
ubuntuvm@ubuntuvm:~$ mkdir Videos/Watched ubuntuvm@ubuntuvm:~$ ls -R Videos

Videos:
Watched
```

Use 
```
ubuntuvm@ubuntuvm:~$ cd Documents
ubuntuvm@ubuntuvm:~/Documents$ mkdir ProjectX Projecty
ubuntuvm@ubuntuvm:~/Documents$ ls
ProjectX Projecty
ubuntuvm@ubuntuvm:~/Documents$
```
### 1. Introduction 

Shell scripting in Ubuntu is a powerful tool for automating tasks, managing
files, and conducting data science experiments. This document provides a com-
prehensive guide, including practical examples related to AI applications.

### 2. Prerequisites

Ensure you have Ubuntu installed, access to a terminal, and basic familiarity
with Linux commands. Knowledge of AI and machine learning concepts is also
beneficial.

### 3. Creating a shell script
**3.1 Using a Text Editor**
You can use text editors like Vim, Nano, or Gedit. For instance, to create a
script with Nano, type:

`nano mt_script.sh                                                                                                       
`
### 3.2 The Shebang Line
Start your script with a shebang (#!/bin/bash) to specify the interpreter for
running your script.

`#!/bin/bash                                                                      `                                                                                                                                                       `
### 3.3 Making the Script Executable
After saving the saving the file, make it executable with :
`chmod +x my_script.sh
`

### 3.4 Running a Shell Script

<img width="1371" alt="image" src="https://github.com/user-attachments/assets/21c986df-9a89-4d36-ba0c-e2d37ada420d">
