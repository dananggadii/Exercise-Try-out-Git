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

## SETUP & INIT
1. Retrieve an entire repository from a hosted location via URL
```
git clone [url]
```

2. Show modified files in working directory, staged for your next commit
```
git status
```

3. Add a file as it looks now to your next commit (stage)
```
git add [file]
git add .
```

4. Unstage a file while retaining the changes in working directory
```
git reset [file]
```

5. Commit your staged content as a new commit snapshot
```
git commit -m “[descriptive message]”
```

6. list your branches. a * will appear next to the currently active branch
```
git branch
```

7. Create a new branch at the current commit
```
git branch [branch-name]
```

8. Switch to another branch and check it out into your working directory
```
git checkout
```

9. Merge the specified branch’s history into the current one
```
git merge [branch]
```

10. Show all commits in the current branch’s history 
```
git log
```
