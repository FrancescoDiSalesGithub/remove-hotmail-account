# remove-hotmail-account
hack to remove hotmail account from windows 11

# How to remove hotmail account

First login-in with your hotmail account in your windows system. Open the cmd and search for the users in your system using the command:
```
net user
```

Usually the hotmail account starts with the first four letters of your hotmail account. Add a local account using the follwing command
```
net user /add mylocaluser mylocaluser
net localgroup Administrator /add mylocaluser
```
This command will create a new user called **mylocaluser** and as password **mylocaluser**

Remove the hotmail account:
```
net user /del myho
```

Now logout from windows and check the login page
