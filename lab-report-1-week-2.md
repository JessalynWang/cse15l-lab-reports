# Lab Report 1

This lab report will cover remote access. We will begin by learning how to install popular code editor VS Code, and end being able to access and interface with course-specific accounts on `ieng6`.

## Part 1: Installing VS Code

![Image](images/Lab1_vscode.PNG)

Here are the steps for installing VS Code. Once completed, you should see something similar to the image above.

1. If you only have access to a tablet or Chromebook, you will not be able to install.
2. Otherwise, go to this [link](https://code.visualstudio.com/) and follow the instructions
3. Once it is installed, you should be able to open VS Code and see something similar to the image above. It might have different colors or less widgets on the sidebar, but that is okay!

## Part 2: Remotely Connecting

1. If you are on Windows, install a program called OpenSSH through this [link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
2. Then, look up your course specific account and make sure to change the password if it has not already been activated here: [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)
3. Then, open VS Code and open a terminal by going to Terminal -> New Terminal in the menu, or using Ctrl/Command `.
4. Next, use the command `ssh [account_username]@ieng6.ucsd.edu`, say yes to the message, and log in using the password you set
5. Now, your terminal should be connected! You should see something similar to the image below

![Image](images/Lab1_sshing.PNG)