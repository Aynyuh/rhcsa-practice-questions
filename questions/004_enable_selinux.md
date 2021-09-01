# Enable SELinux in enforcing mode

### Question:
Enable SELinux in enforcing mode

<details>
  <summary>Click to expand!</summary>

### Answer:

* Make sure that **SELinux** is enabled. This setting can be changed only via reboot! Issue the command **getenforce** and
check what is the status of **SELinux**. If You see **Disabled** then edit the file ***/etc/sysconfig/selinux*** and in a 
proper line change **disabled** to **enforcing**.
* Reboot the system
* Again check **SELinux** status using command **getenforce**
  
</details>
