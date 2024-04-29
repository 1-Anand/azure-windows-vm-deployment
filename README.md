# azure-windows-vm-deployment
Windows Virtual Machine within a pre-existing Azure Virtual Network using the Azure Portal.
## Deploying a Windows VM into an Azure Virtual Network

This project walks through deploying a Windows VM into an existing Azure Virtual Network.

**Technologies:**

* Azure Portal
* Azure Virtual Machines
* Azure Virtual Networks

**Prerequisites:**

* An Azure subscription
* An existing Azure Virtual Network

**Steps**

1. **Log in to the Azure Portal:** Navigate to [https://portal.azure.com](https://portal.azure.com) and sign in with your Azure credentials. 

2. **Create a Virtual Machine:**
   * Search for "Virtual Machines" in the Azure portal and click "Create".
   * **Basics Tab:**
      * Select your subscription and resource group.
      * Provide a name for your virtual machine (e.g., "my-windows-vm1").
      * Choose your desired region.
      * Select "Windows Server" with your preferred version for the OS image.
      * Set an administrative username and password. 
   * **Networking Tab:**
       * Select your existing Virtual Network.
       * Choose an appropriate subnet.
       * Select "Public IP" and choose whether to create a new one or use an existing one. 
   * **Review + Create:**
       * Review your settings and click "Create".

**Additional Notes:**

* **Security:** Consider using Network Security Groups to control traffic to your VM.
* **Customization:** Adjust options like VM size, disks, etc., according to your needs.
