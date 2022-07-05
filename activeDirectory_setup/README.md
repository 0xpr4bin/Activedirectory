# ActiveDirectory Setup VirtualLab Using VirtualBox 

# Virtual Mchines Installing 
 	- Win11 workstation 
 	- windows server 2022 
 	- clone template mode for domain controller and management client 

# Installing Domain Controller 
	1.Use ```SConfig``` to:
		-change hostname
		-change IP address to static 
		-change DNS server to our own IP address 

	2.Install Active Directory windows features 
		
		```Install-WIndowsFeature AD-Domain-Services -IncludemanagementTools``` 
