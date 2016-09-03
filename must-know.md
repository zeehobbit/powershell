Add-ADCentralAccessPolicyMember

Adds central access rules to a central access policy in Active Directory

Add-ADgroupmember PhoenixAdmins PhoenixAdmin01, PhoenixAdmin02

Add members to group
Add-ADResourcePropertyListMember
Adds one or more resource properties to a resource property list in Active Directory
Add-Computer –DomainName domainname.com
Joins a computer to domain
Add-NetSwitchTeamMember
Adds a network adapter member to an existing switch team
Add-PhysicalDisk
Adds a physical disk to storage pool
Add-WindowsFeature
Adds a role or feature
Configure-SMRemoting.exe –Enable
Used to configure a computer running Windows Server 2012 for Remote Management
Configure-SMRemoting.exe –Get
Used to find out if a computer is configured for Remote Management
Enable-ADOptionalFeature –Identity ‘CN=Recycle Bin Feature,CN=Optional Features,CN=Directory Service,CN=Windows NT,CN=Services,CN=Configuration,DC=nuggetlab,DC=com’ –Scope ForestOrConfigurationSet –Target ‘domain.com’
Enable Active Directory Recycle Bin
Enable-NetFirewallRule
Enables a previously disabled firewall rule to be active within the computer or a GP OU
Enable-PSRemoting
Configures the computer to receive Windows PowerShell remote commands that are sent by using the WS-Management technology
Enter-PSSession remote server name -credential user name
Establishes a PS session with a remote computer
Get-ADTrust
Returns all trusted domain objects in the directory
Get-ADUser
Gets one or more Active Directory users
Get-DNSServerGlobalQueryBlockList
List of servers that it does not respond to when the DNS server receives a query to resolve the name in any zone for which the server is authoritative
Get-Help Install-WindowsFeature
Gets the syntax and accepted parameters for the Install-WindowsFeature Cmdlet
Get-NetIPAddress
Gets information about IP address configuration
Get-StoragePool
Show storage pools
Get-VirtualDisk
Show virtual disks
Get-VM –ComputerName <NAME> | Enable-VMResourceMetering
Enable Hyper-V resource metering on Hyper-V host
Get-VM –ComputerName NAME | Measure-VM
To get all VMs metering data
Get-WindowsFeature
Used to get a list of roles and features installed on a computer running Server 2012
Import-GPO
Imports a GPO
Import-Module
Adds module to the current session
Install-ADDSDomain
Installs New Domain
Install-ADDSDomainController
Installs additional DC
Install-ADDSForest
Installs new forest
Install-AddsForest –DomainName “example.com”
Used to promote a server to an Active Directory Domain Controller and make that new DC responsible for a new forest
Install-WindowsFeature
(for remote computer add the –computer flag, as in Install-WindowsFeature <Feature> -Computer <ComputerName>
Adds a role or feature
Install-WindowsFeature –name AD-Domain-Services
Installs Active Directory binaries
Install-WindowsFeature Migration
Adds Migration tools
Install-WindowsFeature –Name Hyper-V –ComputerName<name> -IncludeManagementTools -Restart
Installs Hyper-V on remote computer
Install-WindowsFeature Server-Gui-Mgmt-Infra
Installs Minimal Server Interface from Server Core
Install-WindowsFeature Server-Gui-Mgmt-Infra, Server-Gui-Shell –Restart
Switch from Server Core to Full GUI
Netdom renamecomputer %ComputerName% /NewName: <NewComputerName>
Renames computer
New-ADGroup (with appropriate flags)
Creates a new AD group
New-ADUser
Creates new AD user
New-GPO
Creates a new GPO
New-GPStarterGPO
Creates a new starter GPO
New-NetFirewallRule
New firewall rule
New-NetIPAddress –IPAddress 10.10.10.73 –InterfaceAlias “Ethernet” –DefaultGateway 10.10.10.1 –PrefixLength 24
Configures IP address- Server Core
New-SMBShare –Name Documents –Path D:\Shares
Creates a new SMB Quick share named Documents with the drive label D:
New-StoragePool –FriendlyName –StorageSubSystemFriendlyName –PhysicalDisks
Used to create a storage pool
New-NetRoute –InterfaceIndex 13 –DestinationPrefix 2001:ABCD: /64 –Publish Yes
Configure Network Route for ISATAP Interface
New-NetSwitchTeam
Creates a new switch team (for network traffic failover)
New-VM –Name “VMNAME” –MemoryStartupBytes <memory> -NewVHDSizeBytes <disksize>
Create a Hyper-V virtual machine
Remove-ADCentralAccessPolicy
Creates a new central access policy in Active Directory containing a set of central access rules
Repair-VirtualDisk
Repair virtual disk
Reset-ADServiceAccountPassword
Resets the password for a standalone managed service account. Reset is not supported for group managed service accounts.
Reset-PhysicalDisk
Removes physical disk from storage pool
Restart-Computer
Restarts a computer
Set-DnsClientServerAddress -InterfaceAlias "Ethernet" -ServerAddresses 10.10.10.70, 10.10.10.1
Configure DNS address- Server Core
Set-DNSServerGlobalQueryBlockList
Replaces all names in the list of names that the DNS server does not resolve with the names that you specify (if you need to resolve name  such as ISATAP or WPAD remove these names from the list).
Set-ExecutionPolicy
Enables you to determine which Windows PowerShell scripts will be allowed to run on your computer
Set-NetFirewallProfile
Enable Windows firewall
Set-NetFirewallRule
Modify existing firewall rule
Set-NetIPAddress
Modifies IP address configuration properties of an existing IP address
Set-NetIPInterface
Modifies IP interface properties such as in DHCP, IPv6 neighbor discovery settings, router settings, and Wake on LAN settings.
Set-NetIPv4Protocol
Modifies information about the IPv4 protocol configuration
Set-RemoteDesktop –Enable
Enable Remote desktop connections to the server
Show-WindowsFeatures
List of roles and features installed on a computer
Sync-ADObject
Replicates a single object between any two domain controllers that have partitions in common
Test-ADServiceAccount
Tests a managed service account from a computer
Uninstall-ADDSDomainController –ForceRemoval –LocalAdministratorPassword <password> -Force
Demotes a domain controller
Uninstall-WindowsFeature –Name GPMC –Vhd “path” –Remove
Features on Demand- removes binaries for Group Policy Management Console (can be used for any other feature).
Uninstall-WindowsFeature Server-Gui-Mgmt-Infra, Server-Gui-Shell –Restart (use –Remove before the restart to remove binaries)
Switch from full GUI to Server Core
Uninstall-WindowsFeature Server-Gui-Shell –Restart
Switch from Full to Minimal Server Interface; no IE, taskbar, Windows Explorer, or Control Panel

