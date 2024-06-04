# Install Windows Server
1. Create a new VM and attach the Windows Server ISO.
2. Follow the installation wizard to complete the setup.
3. Assign a static IP address to the server:
   - Open Network and Sharing Center.
   - Change adapter settings.
   - Right-click on your network adapter > Properties.
   - Select Internet Protocol Version 4 (TCP/IPv4) > Properties.
   - Assign a static IP address.

Note: Check ipconfig /all to get gateway, subnetmask and current ip address. Make changes as neccessary. For ease I just made the DHCP allocated address as static.
