
![app](POWERSHELL_SCRIPTS.png)

## Logoff users avoiding service accounts [Link](https://github.com/Martin-kn/Windows-Scripts/blob/main/Logoff_Users(Avoid-accounts-with-REGEX))

What this script does is filter users with disconnected status and then logoff the users. Avoiding disconnecting service accounts.

In this case they are accounts that begin with a letter followed by a period. E.g:

U.XXXXX
P.XXXXX


## Get-Vmtools-version [Link](https://github.com/Martin-kn/Windows-Scripts/blob/main/Get-Vmtools-version)

It is used to verify the version of VMware Tools that the server has with a Try-Catch and if it does not find the VMware Tools path it will mention it.

OUTPUT:

If Vmtools is not installed:
"The VMware path does not exist "

If Vmtools is installed:
"12.3.5.46049"


## Get-FreeDiskSpace-function [Link](https://github.com/Martin-kn/Windows-Scripts/blob/main/Get-FreeDiskSpace-function)

Shows the total space of disk C: and the currently available space
You can add the function to your script and call it by the name that is declared

OUTPUT:
" C: 119.40 GB total, 35.01 GB free "
