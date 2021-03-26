# RaspberryPi4-installkernel.sh

 RPI4 Manjaro installkernel script  
 Fox Chen <foxhlchen@gmail.com>

## Setup:  
   copy /boot/config.txt to /boot/config.txt.origin  
   copy this script to /sbin/installkernel  
  
## Usage:  
   git clone <mainline kernel src code>  
   cd <mainline kernel src code folder>  
   make defconfig  
   sudo make modules_install install  

## Arguments:  
   $1 - kernel version  
   $2 - kernel image file  
   $3 - kernel map file  
   $4 - default install path (blank if root directory)  
