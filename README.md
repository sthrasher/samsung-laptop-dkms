samsung-laptop-dkms
===
This is an updated samsung-laptop kernel module which fixes the keyboard 
backlight of Samsung Series7-Ultra (NP740u3e/NP730u3e) laptop. It should 
work with linux kernels between 3.9 and 3.16 (the changes are in post 3.16 
kernels), on distributions which support dkms. 

Installation
=== 
* copy the samsung-laptop-1 directory to /usr/src
* sudo dkms add -m samsung-laptop -v 1
* sudo dkms build -m samsung-laptop -v 1 -k all
* sudo dkms install -m samsung-laptop -v 1 -k all
* reboot.

License and Warranty
===
* No Warranty
* As this is derivative of the linux kernel, the same license applies; see 
  COPYING
