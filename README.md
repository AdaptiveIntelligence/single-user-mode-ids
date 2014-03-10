
## How it Works
This is a geeklet that runs in GeekTool every 2-10 seconds.  It needs to be used in conjunction with the /var/root/.profile script found at: 
## Requirements
0. Admin computer running OS X 10.8-10.9
1. terminal-notifier installed on the admin computer
2. [GeekTool](http://projects.tynsoe.org/en/geektool/ "Combine GeekTool with this script to sound a klaxon when someone loads Single User Mode and then send the admin a notification") running on a server (it can be any OS X machine; it is just _acting_ as the server).
3. Static IPs set on all machines (preferred) or at least a DHCP reservation
4. SSH keys for passwordless-login between the admin computer and the server
## Usage 
0. Set up a new GeekTool shell module and have it execute once every 2-10 seconds
1. Copy and paste the code in and save it (modifying it per your enviornment)
2. Any time that IP address is pingable, it will send a Notification to the admin 10.8+ computer
3. If the alert it triggered, the admin can then click the Notification to copy the MAC address to the clipboard
4. From there, they can manually paste it into a DB to find which computer it is
## Customizing
## Make Changes to the Variables
Modify the variables to suit the environment (specific IP addresses, usernames, etc.)

