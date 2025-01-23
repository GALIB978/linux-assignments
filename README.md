           Step 1: Create an Azure Account
- Visit the Azure Portal: Go to portal.azure.com
- Sign Up Using HAMK Email: Use student.hamk.fi email to create a free account.
          Step 2: Request Azure for Students Credits
-Log In to Azure Portal: Use student credentials to log in to the Azure account.
-Apply for Student Credits:
-Go to the Azure for Students page.
-Add an "Azure for Students" subscription.
        Step 3: Create a Virtual Machine
-Go to Azure Portal Homepage: Once logged in, navigate to the homepage.
-Create a New Virtual Machine:
-Click on Create a Resource > Virtual Machine.
-Select the OS Image:
-From the Marketplace, choose Ubuntu Server 24.04 LTS Gen 2 published by Canonical.
-Configure the Virtual Machine:
-Name: Use a logical naming convention.
-Size: Select Standard_B2ls_v2 as the virtual machine size.
-Authentication Method: Choose between:
-SSH Key: Generate a public/private key pair and provide the public key during setup.
-Public IP: Ensure a public IP is assigned to allow SSH traffic.
-Resource Group: Create a new resource group to organize the virtual machine.
-Subnet: Set up a new subnet within the virtual network.
-Review and Create: After entering the settings, review your configuration and click Create.
         Step 4: Connect to the Virtual Machine
-Download PuTTY:
-Go to PuTTY’s official website.
-Download the 64-bit x86 MSI package and install it.
-Connect Using SSH:
-Open PuTTY.
-Enter the public IP address of virtual machine in the Host Name field.
-Use the username and password (or username and private key) specified during the VM creation process.
-Click Open to establish the connection.
-Verify Login:
-If everything is set up correctly, you should see the terminal prompt for your Ubuntu Server.# linux-assignments
