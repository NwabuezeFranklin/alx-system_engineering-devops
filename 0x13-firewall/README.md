## Task 1 add 'sudo' where necessary
- apt-get install ufw
- sed -i 's/IPV6=.*/IPV6=yes/' /etc/default/ufw
- ufw disable
- ufw enable
- ufw default deny incoming
- ufw default allow outgoing
- ufw allow 22/tcp
- ufw allow 443/tcp
- ufw allow 80/tcp

### How to manage and forward ports with UFW
https://www.arubacloud.com/tutorial/how-to-manage-and-forward-ports-with-ufw-on-ubuntu-18-04.aspx

## Task 2

### modify your /etc/ufw/before.rules and paste the file as your answer
