# Terminal-Commands
Learn Basic Terminal Commands (Windows)

source: [freecodecamp](https://www.freecodecamp.org/news/command-line-commands-cli-tutorial/)

# Run the Command Prompt as an Administrator
powershell start cmd -v runAs

# Lists All Installed Drivers
driverquery

# Changes the Current Working Directory to the Specific Directory
cd

# Shows Your PC's Details
systeminfo

# Shows your PC's Environment Variables
set

# Changes the Default Text Shown before Entering Commands
prompt

# Copies an Item to the Clipboard
clip

# Lists Programs and the Extensions They are Associated With
assoc

# Changes the Command Prompt Window Title Using the Format title `window-title-name`
title

# Compares Two Similar Files
fc

# Wipes Free Space and Encrypts Data
cipher

# Shows Open Ports, their IP Addresses, and States
netstat -an

# Shows a Website IP Address, lets you Know How Long it takes to Transmit Data and get a Response.
ping

# Changes the Text Color of the Command Prompt
color

# Shows ALL Wi-Fi Passwords (as admin)
for /f "skip=9 tokens=1,2 delims=:" %i in ('netsh wlan show profiles') do @echo %j | findstr -i -v echo | netsh wlan show profiles %j key=clear

# Shows Information about PC IP Address and Connections
ipconfig

# System File Checker (as admin)
sfc

# Controls Configurable Power Settings
powercfg

# Lists Items in a Directory
dir

# Deletes a File
del

# Hides a Folder
attrib +h +s +r 

# Logs on to a Website from the Command Line
start

# Shows the Tree of the Current Directory or Specified Drive
tree

# Shows the Version of the OS
ver

# Shows Open Programs
tasklist

# Terminates a Running Task
taskkill

# Shows and Changes the Current Date
date

# Shows and Changes the Current Time
time

# Shows the Serial Number and Label Info of the Current Drive
vol

# Runs the Deployment Image Service Management Tool
dism

# Stops the Execution of a Command
CTRL + C

# Provides a guide to other Commands
-help

# Shows Custom Messages or Messages from a Script or File
echo 

# Creates a Folder
mkdir

# Deletes a Folder
rmdir

# Shows More Information or the Content of a File
more

# Moves a File or Folder to a Specified Folder
move

# Renames a File with the Syntax
ren

# Clears the Command Line
cls

# Closes the Command Line
exit

# Shuts down, Restarts, Hibernates, Sleeps the Computer
shutdown
