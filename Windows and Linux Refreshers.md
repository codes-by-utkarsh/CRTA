Starting with Some Windows commands that are necessary for the exams. These are very basic commands that we should be knowing and be comfortable with in order to proceed with the exams. 

Windows Commands:

1. whoami - Shows the current user.
2. whoami /all - Shows all the information for the user - username, SID, groups and privileges.
3. hostname - Shows the hostname of the machine.
4. systeminfo - Shows detailed system information(OS version, build, architecture, patches, hostname, domain, etc.).
5. ipconfig & ipconfig /all - Shows network configuration.
6. route print - It shows the routing table of the machine.
7. arp -a - See IP <-> MAC mappings known to machine.
8. netstat -ano - Shows network connections and listening ports.
9. tasklist /svc - Shows running processes and their services.
10. taskkill /f /pid <PID> - Kills the process with the given PID.
11. Get-Process | Where-Object {$_.ProcessName -like "*")
12. net user - Lists all users on the machine. 
13. net user $username - Enumerate local accounts.
14. net localgroup - Lists all groups on the machine. 
15. net localgroup "Administrators" - Shows members of the Administrators group.
16. net accounts - Shows password policy.
17. net group /domain - Lists all domain groups.
18. Get-Location : Shows current directory.
19. Get-ChildItem : Shows all items in a directory.
20. Get-Content file.txt - Similar to cat, like it shows the content of the file.
21. Get-Command python - Find available commands/programs.


MUST BE EFFICIENT WITH :

whoami /all
hostname
systeminfo
ipconfig /all
route print
arp -a
netstat -ano
tasklist /svc

net user
net localgroup
net localgroup administrators

net user /domain
net group /domain
net group "Domain Admins" /domain

sc query
schtasks /query
icacls
where
findstr

Powershell Commands -

Get-ChildItem
Get-Content
Get-Process
Get-Service
Get-NetIPConfiguration
Get-NetTCPConnection
Get-LocalUser
Get-LocalGroup
Get-LocalGroupMember
Get-ScheduledTask
Get-ComputerInfo
Get-Command