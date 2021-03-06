Open In Total Commander
===========================
Author: Björn Carlsson
License: MIT
https://github.com/HackerBaloo/SublimeOpenInTotalCommander

About
-----
A sublime plugin that allows you to open selected file 
(by pressing'ctrl+shift+o') in Total Commander
or other app if you tweek the settings a bit.

Usage
-----
All you need to do is to press 'ctrl+shift+o' and 
Open in Total Commander will open the selected file in Total Commander 
or another app if you have changed the  settings

Configuration
-------------
Default:
    // Environment variabel with path to Total Commander
    // if sublime is started from Total Commander you already have 
    // COMMANDER_EXE 
    // name of environment variable that contains path to executable 
    "path_environment_variable": "COMMANDER_EXE",
    // executable is used, if path_environment_variable is empty, or doesn't exist
    "executable": "C:/Program Files(x86)/Totalcmd/Totalcmd.exe",
    // Fallback if first executable doesn't exist
    "executable2": "C:/Program Files/Totalcmd/Totalcmd64.exe",
    // {path} refers to open file/buffer
    "aruments": "/O /P=L /L=\"{path}\""

On linux if  have tried this:
    // Environment variabel with path to Total Commander
    // if sublime is started from Total Commander you already have 
    // COMMANDER_EXE 
    // name of environment variable that contains path to executable 
    "path_environment_variable": "COMMANDER_EXE",
    // executable is used, if path_environment_variable is empty, or doesn't exist
    "executable": "nautilus",
    // Fallback if first executable doesn't exist
    "executable2": "",
    // {path} refers to open file/buffer
    "aruments": "{path}"


Installation
------------
**With Package Control:** The easiest way to install Open In Total Commander is
by using the [Package Control plugin]
(http://wbond.net/sublime_packages/package_control).

**Without Git:** Download the latest source from 
[GitHub](https://github.com/HackerBaloo/SublimeOpenInTotalCommander) and copy 
the Open In Total Commander folder to your Sublime Text 2 "Packages" directory.

**With Git:** Clone the repository in your Sublime Text 2 "Packages" directory:

    git clone https://github.com/HackerBaloo/SublimeOpenInTotalCommander "Open In Total Commander"

The "Packages" directory can be found in the following locations:

* OS X:

        ~/Library/Application Support/Sublime Text 2/Packages/

* Linux:

        ~/.config/sublime-text-2/Packages/

* Windows:

        %APPDATA%/Sublime Text 2/Packages/

