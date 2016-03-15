# pspad-git
#### local and remote Git commands for PsPad editor

# How to install
Copy the `gitCommands.vbs` file into the `Script\VBScript` directory of PsPad and restart the PsPad editor; 
It will then look like this:

<div align="center">
        <img width="35%" src="/media/images/2016-03-15%2016_38_02-gitCommandsAdded.png?raw=true" alt="git-commands after installation" title="pspad git-commands"</img>
        <img height="0" width="8px">
</div>

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
