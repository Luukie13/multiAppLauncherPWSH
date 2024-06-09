# multiAppLauncherPWSH
a powershell script to launch and close multiple programs/apps at once

# setup
first make sure powershell 7 is installed on your machine. I can only confirm that this script works on windows.
Next is dealing with the execution policy. as of right now the .ps1 is unsigned and im not entirely sure how to change that.

Lastly put the shortcuts you want to launch/close together in the shortcuts folder and launch the .ps1 with powershell 7 (you can set the default app for the program in properties).
Now whenever you close any of the programs launched with the launcher, they all close.
