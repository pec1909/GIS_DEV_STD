# Git

Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

## Installation

[Download Here](https://gitforwindows.org/). You only need the Bash install of Git. The following are the only questions which don't require defaults answers.

|Question|Answer|
|---|---|
|Choosing the default editor used by Git| Use Visual Code as Git's defaults editor|
| Adjusting the name of the initial branch in new repositories | Let Git decide|
|Adjusting your PATH environment | Git from the command line and also from 3rd-party Software|
|Choosing HTTPS transport backend |Use the native Windows Secure Channel Library.|
|Configuring the Line ending conversions| Checkout Windows-Style, commits Unix-Style line endings|
|Configuring the terminal emulator to use with Git Bash | Use Windows defaults console windows.|
|Choose the defaults behavior of git pull | Default|
|Choose a credential Helper| Git Credential Manager|
|Configuring extra options| Enable file system caching|
|Configuring experimental options| |

## set up Git to work with your GitHub account

To ensure that you connect correctly from VS Code to in a bash terminal (can use the  one in VS Code). "your account" is your Github accounts username, "your email" is your Github accounts email. You can find these on your GitHub account tab.

```shell

git config --global user.name "Your account" 
git config --global user.email "Your email"
```

## Useful git commands

```shell
git status
git config --global
git config --list
```
