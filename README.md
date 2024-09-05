
![app](POWERSHELL_SCRIPTS.png)

## Logoff users avoiding service accounts [Link](https://github.com/Martin-kn/Windows-Scripts/blob/main/Logoff_Users(Avoid-accounts-with-REGEX))

What this script does is filter users with disconnected status and then logoff the users. Avoiding disconnecting service accounts.

In this case they are accounts that begin with a letter followed by a period. E.g:

U.XXXXX
P.XXXXX
