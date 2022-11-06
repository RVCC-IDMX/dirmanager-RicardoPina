# Dir Manager

DirManager is a CLI (command line interface) application that allows full directory control while improving readibility and ease of use.

## How to install

To install dirmanager, you need the latest version of node.js and npm install on your machine.

Then on the terminal, you can write the following command to install dirmanager:

`npm i dirmanager-ricardopina`

## Valid commands

To get the list of valid commands, you can type `dirmanager` directly on the terminal.

You can also type `dirmanager -h` which stands for _help_. Both commands will yield the main menu:

![Help menu of dirmanager](img/dir-manager.png)

## List Directory

To list the contents of a directory, you can use one of the following flags. Optionally, you can add an argument to display a specific directory.

`dirmanager -l [optional argument]`

or

`dirmanager -ls [optional argument]`

![Terminal: table listing the contents of a directory](img/list-directory.png)

## Create a directory

To create a directory, you can use one of the following flags followed by the name of the directory:

`dirmanager -m <directory-name>`

or

`dirmanager -mkdir <directory-name>`

![Terminal: confirmation message for creating directory](img/create-directory.png)

## Create a file

To create a file, you can use one of the following flags followed by the name of the file:

`dirmanager -t <file-name>`

or

`dirmanager --touch <file-name>`

![Terminal: confirmation message for creating file](img/create-file.png)

## Version

To check the current version of the application, you can use one of the following flags:

`dirmanager -V`

or

`dirmanager --version`

![Terminal: message showing Dir Manager version](img/version.png)

## Help

As referenced before, to find the help page you can use one of the following flags:

`dirmanager -h`

or

`dirmanager --help`

![Terminal: displays Dir Manager help menu](img/dir-manager.png)
