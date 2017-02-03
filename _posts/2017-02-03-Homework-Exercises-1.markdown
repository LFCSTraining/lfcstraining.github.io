                       
LFCS Homework Tasks   
====================
                                    

 
1. User creation and group management  
----------------------------------                                   
---

### a. Create five users, usernames should be:

- janis
- ieva
- alex
- arturs
- bob

### b. Create group named "project"


### c. Add the five users to the group named "Project"



### d. Set the password for all five user accounts to expire in one month

### e. Change the password for two of the users.


---



2. Directory and file permissions       
------------------------------
---

> ### a. Create directory /home/projects

> ### b. Change the group for directory /home/projects so that it belongs to the  "projects"

> ### c. Change permissions on /home/projects so that it has read/write access to any user in the group "projects"

> ### d. Change permissions on /home/projects so that it is not available to any other users.

> ### e. Change the owner of the /home/projects user to one of the five users created

---


                                   
3. Sudo                              
-------                                 
---

### a. Allow all users in the projects group to have root access using sudo

### b. Use sudo to obtain an interactive root shell.

---

4. Basic Process Management                    
------------------------
---


### a. Use the 'top' utility to view all of the running processes on the system

### b. kill all of the bash processes. This might log you out of the system. Why is this?

### c. Reduce the priority of a process

### d. Increase the priority of a process

---


5. Hostname and timezone 
---------------------
---

### a. Use hostnamectl to set the hostname of the system to LinuxTraining

### b. Change the timezone to Europe/Riga

### c. Synchronise the system time with the remote NTP server 3.lv.pool.ntp.org

---
                       
6. Package Management     
------------------                       

### a. Upgrade all packages which exist on the system using yum

- Install the package 'tmux'
- Remove the package 'tmux'

### b. Find which installed package has provided the following files using the rpm utility

- /usr/bin/grep
- /usr/bin/yum
- /usr/bin/ls

### c. download the following package using wget

[https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-alpha.14/powershell-6.0.0_alpha.14-1.el7.centos.x86_64.rpm](https://github.com/PowerShell/PowerShell/releases/download/v6.0.0-alpha.14/powershell-6.0.0_alpha.14-1.el7.centos.x86_64.rpm)

### d. Install the package using the rpm utility

### e. This package requires a prerequisite package. Find out how to resolve this dependency issue by installing the prerequisite.

### f. Use yum to find which package provides the following file: nmap

### g. Use rpm -qd to find the documentation available for a utility, for example, grep

---

7. Backup using tar and gzip  
-------------------------
                           
### a. Backup all files on the system to the directory /home/backup/backup.tar using the tar utility

### b. Preserve all permissions for files

### c. Compress the /home/backup/backup.tar using gzip

---

                                        
8. Using Cron the schedule automatic jobs 
--------------------------------------                                      
---

### a. Schedule an automatic backup job using cron which backs up all the files to /home/backup/backup.tar 

---
                                          

9. Basic Service Management                 
------------------------                                        
---

### a. Install the package: httpd

### b. Start the httpd service using: systemctl start httpd

### c. Use systemctl to observe if httpd.service is running

### d. Change directory to /etc/systemd/system

### e. Use ls to view the targets available

### f. Use systemctl to find out which target is the default

### g. Change directory to /etc/systemd/system/multi-user.target.wants

### h. stop httpd.service using systemctl

### i. Create a symlink between /usr/lib/systemd/system/httpd.service and /etc/systemd/system/multi-user.target.wants/httpd.service

### j.Restart the computer

### h. is httpd running after restart? If so, why?

### i. Disable the httpd service from starting automatically at system startup using systemctl

### j. Does the link at /etc/systemd/system/multi-user.target.wants/httpd.service still exist? why or why not?


---




