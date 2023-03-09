## azure-network-rbac-with-ipgroup-firewall  

### Problem Statement  

How can be we allow per user-level (per VM) to access only certain VLANs on-premises or certain VNet/Subnets on Azure,  
and also having friendly identifier/labelling to each user/VM, so that managing the network firewall rules will be less error-prone

### Solution  

* Create an IP Group for each user (or group of users) using either the username as IP Group name
* Use Azure Firewall Network Rule with IP Group to achieve user-level network access control.
