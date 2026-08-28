# Bash Script (Shell Script) Execution Steps

## Introduction

This is a Bash file (w/ `.sh` extension) execution instruction. Before starting, you must be sure that you have already provided the infrastructures required for Shell Scripting.

## Features

- Creating `.sh` extended files
- Executing `.sh` extended files
- Applying some Linux CLI commands
- Giving permissions to the files via Linux CLI commands

## Prerequisities

1. Linux
2. Ubuntu
3. VirtualBox or VMWare (It depends on you how to use Linux as a VM or a secondary operating system)
>[!NOTE]
> If you use Linux (Ubuntu) as Virtual Machine, then you must download VirtualBox or VMWare which is up to you to use.
> Else you do not have to download meaning where you use Linux as secondary OS.
> In this instruction, Linux (Ubuntu) is used as VM

## Steps

1. Create your bash file via the command the below
```
  touch filename.sh
```
2. Open the file from your File Explorer in which you created the file based on the path.
3. Write your bash code in the file.
4. Open the Command Line Interface when you're done coding the bash file.

>[!IMPORTANT]
> After the fourth step, the steps will be done on Linux CLI

5. Set the path for which you create the bash file via the command below
```
  cd your_path_for_your_bash_file
```
6. Give the permission to execute the file via the command the below
```
  chmod u+x (+x) filename.sh
```
7. Execute the bash file via the commands below
```
  ./filename.sh (Alternative 1: Run Executable File) (Preferred generally)
  bash filename.sh (Alternative 2: Run without permission)
  bash -x filename.sh (Alternative 3: Debug while running )
```

## Technologies & Programs (Used)

![VirtualBox](https://img.shields.io/badge/VirtualBox%20-%20%232F61B4?style=for-the-badge&logo=virtualbox)
![Linux](https://img.shields.io/badge/Linux%20-%20%23FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu%20-%20%23E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash%20-%234EAA25?style=for-the-badge&logo=gnubash&logoColor=black)



