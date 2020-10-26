 Chrony
* Purpose – Time Synchronization
* Package name – chronyd 
* Config file - /etc /chrony.conf 
* Log file -/var/log/chrony
* Service – systemctl start /restart chronyd
* Program  command – chronyc
### Step 1 -> Install the package : 

     *  yum install -y chrony

### Step 2 -> Edit /etc/chrony.conf file  
     * vi /etc/chrony.conf
     * add server 8.8.8.8( google server address to get time synced in our server ) where all the server listed in file
     
 <img src="images./adding google server.PNG" height=200>
 
 
