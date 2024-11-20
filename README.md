# Exercise Try out Git

## Configure Git
1. In Cloud Shell, to double-check that Git is installed, type git --version:
```
git --version
```

2. Set your name in Cloud Shell with the following command. Replace <USER_NAME> with the user name you want to use.
```
git config --global user.name "<USER_NAME>"
```

3. Now, use this command to create a user.email configuration variable, replacing <USER_EMAIL> with your e-mail address:
```
git config --global user.email "<USER_EMAIL>"
```

4. Run the following command to check that your changes worked:
```
git config --list
```

![image](https://github.com/user-attachments/assets/2754affc-4a41-476e-a259-d052f504020c)

## Set up your Git repository
1. Create a folder named. This folder will be the project directory, also called the working tree. The project directory is where all files related to your project are stored. In this exercise, it's where your website and the files that create the website and its contents are stored.
```
mkdir "<FOLDER_NAME>"
```

2. Change to the project directory by using the cd command:
```
cd "<FOLDER_NAME>"
```

3. Now, initialize your new repository and set the name of the default branch to main:
```
git init -b main
```

4. Now, use a git status command to show the status of the working tree:
```
git status
```

5. Use an ls command to show the contents of the working tree:
```
ls -a
```
> **NOTE** : 
> Confirm that the directory contains a subdirectory named .git. (Using the -a option with ls is important because Linux normally hides file and directory names that start with a period.) This folder is the Git repository—the directory in which Git stores metadata and history for the working tree.
