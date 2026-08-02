# Git-Push-Action

## Introduction

This is an instruction for Git about how to do a push into a branch (usually main)

## Features

- Cloning repositories
- Examining branch status
- Pushing updates into the branches
- Adding changes via git
- Creating commits

## Requirements

- To handle this, you have to download Git Bash to your device. You could benefit this Youtube video below. To go to YouTube, press the badge

  [![Youtube](https://img.shields.io/badge/Youtube%20-%20%23FF0000?style=for-the-badge&logo=youtube&logoColor=white)
  ](https://www.youtube.com/watch?v=t2-l3WvWvqg)

- Visual Studio Code (Generally used)
- GitHub Account


## Steps
> [!WARNING]
> Before starting, you should apply these steps on your command terminal or CLI. Therefore, you had better check whether Git has successfully been uploaded
> To check it, you could enter this command:
> ```
> git --version
> ```

1 - Clone the repository (Use HTTPS code from GitHub)
```
git clone https://github.com/username/repository_name.git
```
2 - Go to the repository
```
cd repository_name
```
3 - Check the current branch
```
git branch
```
If you see `* main`, then it means you are at `main` branch

4 - Go to the Visual Studio Code (It's used here), 
```
code
```
Then Visual Studio will be opened so you could make changes on the code

5 - After the changes, check the status using the command
```
git status
```

6 - Add the changes
```
git add .
```

7 - Create a commit into the current branch
```
git commit -m "Your Text"
```

8 - Push changes into the branch
```
git push origin main
```
> [!WARNING]
> If you push for the first time, then you should enter the command below because it may not push the changes when you enter the command above.
> To push the changes (if first time), enter the command below 
> ```
> 
> git push -u origin main
>
> ```

9 - After the push, you should control whether your changes has been successfully added to the branch

## Technologies

![Git](https://img.shields.io/badge/Git%20-%20%23F03C2E?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub%20-%20%23181717?style=for-the-badge&logo=github&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode%20-%20blue?style=for-the-badge)
![Command Prompt](https://img.shields.io/badge/Command%20Prompt%20-%20black?style=for-the-badge)






