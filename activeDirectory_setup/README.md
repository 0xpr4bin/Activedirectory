# ActiveDirectory Setup VirtualLab Using VirtualBox 

# Virtual Mchines Installing 
 	- Win11 workstation 
 	- windows server 2022 
 	- clone template mode for domain controller and management client 

# Installing Domain Controller 
> Use `SConfig` to:
- change hostname
- change IP address to static 
- change DNS server to our own IP address 

> Install Active Directory windows features 
 - `Import-Module -Name ActiveDirectory`
 - `Install-WIndowsFeature AD-Domain-Services -IncludemanagementTools`
 - `Install-ADDSForest -DomainName domain.local -InstallDNS `
  
> Change Dns setting 
 - `Get-NetIPAddress`
 - `Get-DnsClientServerAddress`
 - `Set-DnsClientServerAddress -InerfaceIndex [no] -ServerAddress [ip of dns]`
  
  
