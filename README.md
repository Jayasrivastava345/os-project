# os-project
This is the code for my Operating systems minor course.

The code in this repository corresponds to the programming project of Chapter 2 on Linux Kernel Modules from the 10th edition of Operating System Concepts.

Designed a kernel module that creates a /proc file named /proc/jiffies
that reports the current value of jiffies when the /proc/jiffies file
is read, such as with the command :

cat /proc/jiffies

Designed a kernel module that creates a proc file named /proc/seconds
that reports the number of elapsed seconds since the kernel module was
loaded. This will involve using the value of jiffies as well as the HZ
rate. When a user enters the command:

cat /proc/seconds
