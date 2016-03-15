# pspad-git
#### local and remote Git commands for PsPad editor

# How to install
Copy the *gitCommands.vbs* file into the `Script\VBScript` directory of PsPad

## Prerequisites: 
GIT should already be installed and available 
in the path environment variable, accessible from everywhere.

The first thing to do when Git is installed is 
to set your user name and email address. 
```
   git config --global user.name "John Doe"
   git config --global user.email johndoe@example.com
```

This is important because every Git commit uses this information, 
This information will be stored in the local file `.git\config` file
```
[user] 
   user.name=John Doe
   user.email=johndoe@example.com
```
