# AD Tools
A collection of scripts to interact with Windows Active Directory via PowerShell.

## Requirements
To work this scripts it's necessary has been installed and import the ActiveDirectory module.

Fill the variables on ADconfig.conf file to customize the scripts for your AD installation.

## List of scripts
- eternumPasswords.ps1
  + (Shows a list of accounts with "Never Expires" field is checked)
- noExpiredPasswords.ps1
  + (Shows a list of accounts with the follow properties: Enabled,  the password is not expired and "Never Expires" field unchecked)
- expiredPasswords.ps1
  + (Shows the list of accounts with the password expired)
