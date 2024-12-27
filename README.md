# AD_Labs

##

## Lab 1
Created a VM using Virtual Box housing Windows Server 2022 (referred to as VM1)

## Lab 2
Renamed PC
Set up a new forest with Active Directory Domain Services


## Lab 3
CMD commands: 
* `ipconfig`
* `ipconfig /all`
* `net use` (for shared drives)
* `net user <user> /domain` (for password history and permissions)
Created a helpdesk account with Active Directory Users and Computers
Searching “Entire Directory”
View “Advanced Features” for objects
Enable recycle bin with Active Directory Administrative Center


## Lab 4
Added a static IP address to Server 2022
Created a new VM using Virtual Box housing Windows 10 Pro (referred to as VM2)
Enabled admin account and removed the user account
Configured admin account for helpdesk by downloading RSAT tools from optional features
Downloaded Google Chrome and Teamviewer to admin account
Renamed VM2 and connected it to VM1 domain 

## Lab 5
On VM2, added an organizational unit (OU) named _IT
Used a PowerShell script to add several users to the newly created _IT OU
Moved helpdesk account to _IT
Reviewed Resultant Set of Policy (RSOP), which is the group policies of that user account
Reviewed Group Policy Management (screenshot password info of domains for reference)
Created another Windows 10 Pro VM (referred to as VM3)
Double checked that recycle bin is enabled
Configured everything on VM3 the same way as VM2 (can use either one for quicker labbing)

## Lab 6
CMD commands:
* `ping`
* `ping <ip address> -t`
* `gpresult  /user <name> /r  >c:\result`
* `gpupdate /help`
Unlocking a locked account
Disabling and enabling accounts
Disabling and enabling computers
Changing passwords


## Lab 7
“File and Storage Services” Shares
Security Groups
Mapped drives 
Personal Drives
Map lettering using Active Directory

## Lab 8
CMD commands:
* `ipconfig /flushdns`
Enable remote desktop settings
Remote into desktop using Remote Desktop Connection
Drives and AppData
Regedit (for checking shared drives without bothering users)
C$
Invite someone to connect to your PC

## Lab 9 
CMD commands
* `gpupdate /force` (logoff necessary for desktop level but not user level)
* `gpupdate /?`
* `gpresult /r`
Group policy
Group policy admin permission override
Group Policy Results Wizard
Active Directory Users and Computers RSOP report



## Lab 10
Tier 2+
Installing PDQ
Deploying PDQ
Software packages


## Lab 11
PDQ Inventory
Software inventory management
Hardware inventory check
Applications (Adobe, Zoom, etc.)
SCCM

## Lab 12
Print and Document Services through Server Manager
Print Management
Add groups to OUs
PrinterCloud

## Lab 13
Spiceworks <br /> <br />
![ticket map outline](https://github.com/bqazi/AD_Labs/blob/main/ticket_map.png) <br /> <br />
Creating a ticket
Assigning a ticket
Closing the ticket and putting notes on it - basic documentation
join.zoho.com

## Lab 14
Delegate control
Microsoft account lockout tool

