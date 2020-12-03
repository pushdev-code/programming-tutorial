# Terminal

* Operating system: manages the computer's memory and processes, as well as all of its software and hardware.

![image](https://user-images.githubusercontent.com/36536646/82505392-3f542200-9ac3-11ea-92e0-a3e2ae28ea25.png)

Have you ever heard about shell, cmd, cli, terminal, bash... ?

![image](https://user-images.githubusercontent.com/36536646/82504582-614ca500-9ac1-11ea-8668-60a8479928f7.png)

Don't be afraid... we are not hackers...

### What is a terminal?

The terminal is a program that takes commands from the keyboard and gives them to the operating system to perform. 

![image](https://user-images.githubusercontent.com/36536646/82505137-a32a1b00-9ac2-11ea-9709-dac1a2bd855c.png)

In the old days, you had to use the shell, there was no other option.

Nowadays, we have graphical user interfaces (GUIs) in addition to command line interfaces (CLIs) such as the shell.

![image](https://user-images.githubusercontent.com/36536646/82505524-94903380-9ac3-11ea-804a-4ef36d6178c9.png)

* However, cmd is relatively limited in today's world. PowerShell (2006) provides command-line syntax and scripting sintax. You can query and manipulate objects far more easily than you can process text. It’s more powerful and uses different commands altogether.

### List of commands

* [macOS](https://ss64.com/osx/)
* [linux](https://ss64.com/bash/)
* [windows](https://ss64.com/nt/)

* **`$`** means the beginning of the command.

#### Current directory

* macOS: `$ pwd`
* linux:  `$ pwd`
* windows:  `$ cd`

#### Move to another folder

* macOS: `$ cd Documents`
* linux: `$ cd Documents`
* windows: `$ cd Documents`

#### Go back

* macOS: `$ cd ..`
* linux: `$ cd ..`
* windows: `$ cd ..`

#### Show files of the current folder

* macOS: `$ ls`
* linux: `$ ls`
* windows: `$ dir`

#### Create new folder

* macOS: `$ mkdir name_of_your_folder`
* linux: `$ mkdir name_of_your_folder`
* windows: `$ mkdir name_of_your_folder`

#### Create new file

* macOS: `$ echo "hello push" > myfile.txt`
* linux: `$ echo "hello push" > myfile.txt`
* windows: `$ echo "hello push" > myfile.txt`

#### Check file content

* macOS: `$ type myfile.txt`
* linux: `$ cat myfile.txt`
* windows: `$ type myfile.txt`

#### Remove file

* macOS: `$ rm myfile.txt`
* linux: `$ rm myfile.txt`
* windows: `$ del myfile.txt`

#### Remove folder

* macOS: `$ rmdir name_of_your_folder`
* linux: `$ rmdir name_of_your_folder`
* windows: `$ rd myfile.txt`

### Facts

* `tab` key helps you to complete the commands.
* ↑ ↓ Arrow keys help you to navigate through the commands.
* If you want to learn Git, you should learn how to use the shell.
* Using the shell puts you in full control of your computer and your workflow.
* You would look like a hacker in front of your friends. 
* If you want to be a Git master you must know how to use the terminal.

### Install linux shell Windows 10

* [How to install ](https://ubuntu.com/tutorials/tutorial-ubuntu-on-windows#1-overview)

### Let's play.

* We have the snake game in Linux terminal thanks to nSnake. 
* Use the command below to install it.

`sudo apt-get install nsnake`
`nsnake`

![image](https://user-images.githubusercontent.com/36536646/82739872-2f2d8400-9d09-11ea-972d-ebb15e5eb57a.png)

![image](https://user-images.githubusercontent.com/36536646/82739893-48cecb80-9d09-11ea-8563-965cbd510638.png)

[More games](https://itsfoss.com/best-command-line-games-linux/)

# Version Control Systems - GitHub

Tool that allow to identify, store and control access to the different versions of the components.

Many different version management systems are available, including widely used open source systems like CVS, Subversion, GitHub, GitLab,
Bitbucket etc.

![image](https://user-images.githubusercontent.com/61557537/82740684-bdf1cf00-9d10-11ea-81cc-c9648cdf9f83.png)

## What is Version control?

* Version management: Process of monitoring the different versions of software components or configuration items, and the systems where these components are used.

![image](https://user-images.githubusercontent.com/61557537/82740458-86822300-9d0e-11ea-9d21-6c8477e0eb21.png)

* Changes made to such versions by different developers do not interfere with each other.

Advantages:

* Don't lose track of changes and versions.
* Avoid problems with the existence of several functional versions of the system.
* Optimize time and reduce errors.
* All changes made to the code of a system or component are logged and listed.
* It involves tagging components with keywords that describe the changes made.

![image](https://user-images.githubusercontent.com/61557537/82740835-fa71fa80-9d11-11ea-9327-1e360ed0cb2e.png)

## What is Git and GitHub?

* Git is a revision control system, a tool to manage your source code history.
* GitHub is a hosting service for Git repositories.

So they are not the same thing: Git is the tool, GitHub is the service for projects that use Git.

![image](https://user-images.githubusercontent.com/61557537/82740843-0d84ca80-9d12-11ea-9255-2a4d3d25aeda.png)

### Git

Git is a distributed version control tool that can manage a development project's source code history.

### GitHub

GitHub is a cloud based platform built around the Git tool.

* Different developers may work on the same component at the same time.
* The version management system tracks the components that have been marked for editing.
* It also ensures that changes made to a component by different developers do not interfere.

### Sources

* [Shell](http://linuxcommand.org/lc3_lts0010.php)
* [Difference between cmd, PowerShell and Bash](https://www.youtube.com/watch?v=nahtw_csB5w)
* [Git vs GitHub](https://kinsta.com/knowledgebase/git-vs-github/)
* SWEBOK, 6: IEEE Computer Society. SWEBOK: Guide to the Software Engineering Body of Knowledge, 2014.
