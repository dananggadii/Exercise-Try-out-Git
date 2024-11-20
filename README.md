# Exercise Try out Git

## Configure Git
1. In Cloud Shell, to double-check that Git is installed, type git --version:
```
git --version
```
> You can use the Copy button to copy commands to the clipboard. To paste, right-click on a new line in the Cloud Shell terminal and select Paste, or use the Shift+Insert keyboard shortcut (⌘+V on macOS).

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
