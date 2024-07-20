# linuxBasics

### File and Directory Operations:

List directory contents.                      
```
ls                           
``` 

cd: Change directory.                                    
pwd: Print the working directory.                           
mkdir: Create directories.                    
rmdir/rm: Remove directories/files.                        
mv: Move or rename files/directories.                          
cp: Copy files/directories.                                 
find: Search for files and directories.                                     


File Manipulation:

cat: Concatenate and display file content.                                            
less/more: View file content page by page.                                       
head/tail: Display the beginning/end of a file.                                                 
touch: Create an empty file or update timestamps.                                           
grep: Search for text using patterns.                                                             
sed: Stream editor for text manipulation.                                                    

Text Editors:

nano, vim, emacs, or vi: Popular text editors for Linux


User and Permission Management:

sudo: Execute commands with superuser privileges.                              
adduser/userdel: Add or delete user accounts.                                                    
addgroups : to add groups                                

Force user to change password after login: sudo chage -d 0 <username>                               
passwd: Change user passwords.                                   
chown/chmod: Change file/directory ownership and permissions.                              

To add user to a perticular group : sudo usermod -aG <groupname> <username>                       

View Groups : cat/etc/group                        
view users are added in which all group : groups <username>                      
view all members in a group : members groupname / getent group <groupname>                                                    


Process Management:

ps: List running processes.                                     
top/htop: Monitor system processes.                                     
kill: Terminate processes.                                           
nice/renice: Adjust process priority.                                       



Package Management:

apt/apt-get: Package management for Debian/Ubuntu.                                     
yum/dnf: Package management for Red Hat/CentOS.                                              



System Information:

uname: Display system information.                                          
df/du: Disk space usage.                                          
free: Display system memory usage.                                                      
Turw off :   sudo swapoff -a && sudo sed -i '/\bswap\b/d' /etc/fstab                                      
cat /proc/snaps                                                 

Networking:

ifconfig/ip: Network configuration.                                  
curl ifconfig.me                                                 
ping: Test network connectivity.                                                  
netstat/ss: Network statistics                                            
ssh: Secure shell for remote access.                                             
scp: Securely copy files between hosts.                                      
