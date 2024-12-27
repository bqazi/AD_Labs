# AD_Labs

##

## Lab 1
Created a VM using Virtual Box housing Windows Server 2022 (referred to as VM1) <br>

## Lab 2
Renamed PC <br>
Set up a new forest with Active Directory Domain Services <br>


## Lab 3
CMD commands:
- `ipconfig` <br>
- `ipconfig /all` <br>
- `net use` (for shared drives) <br>
- `net user <user> /domain` (for password history and permissions) <br>

Created a helpdesk account with Active Directory Users and Computers <br>
Searching “Entire Directory” <br>
View “Advanced Features” for objects <br>
Enable recycle bin with Active Directory Administrative Center <br>


## Lab 4
Added a static IP address to Server 2022 <br>
Created a new VM using Virtual Box housing Windows 10 Pro (referred to as VM2) <br>
Enabled admin account and removed the user account <br>
Configured admin account for helpdesk by downloading RSAT tools from optional features <br>
Downloaded Google Chrome and Teamviewer to admin account <br>
Renamed VM2 and connected it to VM1 domain  <br>

## Lab 5
On VM2, added an organizational unit (OU) named _IT <br>
Used a PowerShell script to add several users to the newly created _IT OU <br>
Moved helpdesk account to _IT <br>
Reviewed Resultant Set of Policy (RSOP), which is the group policies of that user account <br>
Reviewed Group Policy Management (screenshot password info of domains for reference) <br>
Created another Windows 10 Pro VM (referred to as VM3) <br>
Double checked that recycle bin is enabled <br>
Configured everything on VM3 the same way as VM2 (can use either one for quicker labbing <br>)

## Lab 6
CMD commands:
- `ping` <br>
- `ping <ip address> -t` <br>
- `gpresult  /user <name> /r  >c:\result` <br>
- `gpupdate /help` <br>

Unlocking a locked account <br>
Disabling and enabling accounts <br>
Disabling and enabling computers <br>
Changing passwords <br>


## Lab 7
“File and Storage Services” Shares <br>
Security Groups <br>
Mapped drives  <br>
Personal Drives <br>
Map lettering using Active Directory <br>

## Lab 8
CMD commands:
- `ipconfig /flushdns` <br>

Enable remote desktop settings <br>
Remote into desktop using Remote Desktop Connection <br>
Drives and AppData <br>
Regedit (for checking shared drives without bothering users) <br>
C$ <br>
Invite someone to connect to your PC <br>

## Lab 9 
CMD commands
- `gpupdate /force` (logoff necessary for desktop level but not user level)
- `gpupdate /?`
- `gpresult /r` <br>

Group policy <br>
Group policy admin permission override <br>
Group Policy Results Wizard <br>
Active Directory Users and Computers RSOP report <br>



## Lab 10
Tier 2+ <br>
Installing PDQ <br>
Deploying PDQ <br>
Software packages <br>


## Lab 11
PDQ Inventory <br>
Software inventory management <br>
Hardware inventory check <br>
Applications (Adobe, Zoom, etc.) <br>
SCCM <br>

## Lab 12
Print and Document Services through Server Manager <br>
Print Management<br>
Add groups to OUs<br>
PrinterCloud<br>

## Lab 13
Spiceworks <br> <br>
![ticket map outline](https://github.com/bqazi/AD_Labs/blob/main/ticket_map.png) <br> <br>
Creating a ticket<br>
Assigning a ticket<br>
Closing the ticket and putting notes on it - basic documentation<br>
join.zoho.com<br>

## Lab 14
Delegate control <br>
Microsoft account lockout tool <br>

