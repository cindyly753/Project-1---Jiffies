# Project 1 - Jiffies

This assignment will involve designing two kernel modules: 

1. Design a kernel module that creates a /procfile named /proc/jiffiesthat reports the current value of jiffieswhen the /proc/jiffiesfile is read, such as with the command cat /proc/jiffiesBe sure to remove /proc/jiffieswhen the module is removed. 

2. Design a kernel module that creates a procfile named /proc/secondsthat reports the number of elapsed seconds since the kernel module was loaded. This will involve using the value of jiffiesas well as the HZrate. When a user enters the command cat /proc/secondsyour kernel module will report the number of seconds that have elapsed since the kernel module was first loaded. Be sure to remove /proc/seconds when the module is removed. 
