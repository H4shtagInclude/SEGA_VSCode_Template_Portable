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


### Building your sega genesis/mega drive game.
Open up Visual Studio Code and open the cloned directory 


=== Setup

* Extract SGDK to a prefered directory.
* Create an environment variable `GDK` pointing to the SGDK directory (e.g. "C:/dev/sgdk").
* Install Visual Studio Code.
* Install the following extensions in vsCode: `C/C++ for Visual Studio Code`
* Clone this github repo: `git clone https://github.com/pleft/SEGA_VSCode_Template.git`.

=== Usage

* Open `VSCode` and `File->Open Folder...` and choose the folder of the checked out repository.
* Folder `.vscode` contains two files: `c_cpp_properties.json` and `tasks.json`
    * In `c_cpp_properties.json` it is added the include folder of the `SGDK`: `"includePath": ["${GDK}/inc"]`
    * In `tasks.json` there are 2 tasks to help build and clean the project, `make` and `clean`. 
        - To run `make` task press `Ctrl-Shift-B`.
        - To run `make` or `clean` press `Ctrl-P` then write `task make` or `task clean`.
