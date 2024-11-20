# Exercise Try out Git

## 1. Configure Git
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

## 2. Set up your Git repository
1. Create a folder named. This folder will be the project directory, also called the working tree. The project directory is where all files related to your project are stored. In this exercise, it's where your website and the files that create the website and its contents are stored.
```
  mkdir "<FOLDER_NAME>"
```
