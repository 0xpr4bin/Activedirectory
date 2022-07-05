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
  `Install-WIndowsFeature AD-Domain-Services -IncludemanagementTools`
