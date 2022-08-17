# SGDK Visual Studio Code Template

### Getting the code
* To get the code all you need to do is clone the repository with this simple command.  
```bat
git clone https://github.com/H4shtagInclude/SEGA_VSCode_Template_Portable.git --recursive
```

* If you get an error like...  
*'git' is not recognized as an internal or external command,
operable program or batch file.*  
you most likly need to install git either by going to [Git for Windows](https://git-scm.com/download/win) or using the [Chocolatey Package Manager](https://chocolatey.org/install)  
~~If you are of the special type, you can also use [Winget](https://docs.microsoft.com/en-us/windows/package-manager/winget/)~~

   * Installing git with Chocolatey
     ```bat
     choco install git
     ```
   * Installing git with Winget
      ```bat
      winget install git
      ```


### Making a workspace for your project
This is quite simple, just open up Visual Studio Code and press `Control + K or Control + O` to open a directory or `File > Open Folder`.  
You will get a prompt asking if the directory is safe to open, click `Yes, I trust the authors.` ~~This can be changed later~~  

Now you've got a temporary workspace, you can save it by going to `File > Save Workspace As...`

### Building your sega genesis/mega drive program.
~~Emphasis on the word "Program" as the SGDK can be used for more than Game Development.~~
To instantly build your program just press `Control + Shift + B` or `Terminal > Run Build Task`
