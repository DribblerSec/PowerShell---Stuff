# PowerShell---Stuff
Powershell Script for grabbing OS information - Aim is to profile a system quickly using either usb pendrive or by packaging this in with an installer.

This was a quick write up with a friend, inspired by mimikatz and msf powershell based exploits

Please note, You will need to change the directory for instances of Out-File -filepath eg. Out-File -filepath C:\Users\%username%\Desktop\Stuff
in order to determine where you want file output to go, as the console executes silently.

If you are having issues testing out the script, try running it inside the powershell ISE, or executing as admin.
For the time being, you will need to execute as admin, as I have not yet implemented privilige escalation and will not be right now.

there is a small entry to the code for a execution bypass, that method i've found to be old and am working on a new method,
If you know one, feel free to let me know.

