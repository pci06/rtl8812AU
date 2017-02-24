# rtl8812AU
For driver details see https://github.com/diederikdehaas/

## DKMS
[DKMS](http://linux.dell.com/dkms/) is a system which will automatically recompile and install a kernel module when a new kernel gets installed or updated.
To make use of DKMS, install the `dkms` package, which on Debian (based) systems is done like this:
```
# apt-get install dkms
```
Where '#' denotes that it should be executed as root or with sudo, but don't type that character.

To make use of the DKMS feature with this project, do the following:
```
# make -f Makefile.dkms install
```

Tested device:
[USB id 0bda:8812 Realtek Semiconductor Corp. RTL8812AU 802.11a/b/g/n/ac WLAN Adapter] : https://www.amazon.fr/gp/product/B01BSW2LUU/ref=oh_aui_detailpage_o03_s00?ie=UTF8&psc=1


## Kernel
Kernel 4.9.6
### Load module
In the etc/ directory you can find example.


## Hostapd
Hostapd (patched) v2.4  (patch incoming)
AP Mode OK
Hostapd Dual Band configuration with two AP (2g & 5g): in progress
