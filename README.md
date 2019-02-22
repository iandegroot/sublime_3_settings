# Importing/Exporting Sublime 3 Settings
Set up to save my Sublime 3 settings, so that they can be transferred easily to new machines.

The User directory is typically here: **C:\Users\degroot\AppData\Roaming\Sublime Text 3\Packages\User**

## Syncing User Data

(from https://packagecontrol.io/docs/syncing)

To properly sync your installed packages across different machines, you actually do not want to sync the whole Packages/ and Installed Packages/ folders. The reason for this is that some packages have different versions for different operating systems. By syncing the actual package contents across operating systems, you will possibly run into broken packages.

The proper solution is to install Package Control on all machines and then to sync only the Packages/User/ folder. This folder contains the Package Control.sublime-settings file, which includes a list of all installed packages. If this file is copied to another machine, the next time Sublime Text is started, Package Control will install the correct version of any missing packages.

## Installing Package Control

Follow instructions [here](https://packagecontrol.io/installation).
