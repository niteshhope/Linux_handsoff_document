Chrony
Purpose – Time Synchronization
Package name – chronyd
Config file  /etc /chrony.conf 
Log file  /var/log/chrony
Service – systemctl start /restart chronyd
Program  command – chronyc

Step 1 -> Install the package : -  yum install -y chrony
Step 2   go to  /etc/chrony.conf file  add google server  address
vi /etc/chrony.conf 
add below line 
server 8.8.8.8
and save the file 
adding imange




<img src="images./image.PNG" height=200>
