#WEB SOLUTION WITH WORDPRESS

Step 1: Creating an AWS instance & Connecting to it using Windows Terminal

Launch an EC2 instance that will serve as "Web Server". Create 3 volumes in the same AZ as your Web Server EC2, each of 10 GiB.

Attach all three volumes one by one to your Web Server EC2 instance

Step 2: COnfiguring the volumes

Use lsblk command to inspect what block devices are attached to the server



Use df -h command to see all mounts and free space on your server

Use gdisk utility to create a single partition on each of the 3 disks
