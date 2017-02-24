#Hostapd
The directory hostapd/ contains stuff to ease creating an AP

## Get hostapd source v2.4

Example:
```
# apt-get source hostapd=2.4-0ubuntu6
```

The command above retrieve the wpa source tree which contains hostapd for a debian like distribution

##Patch the source tree
Change directory to the wpa source tree
```
patch -p1 < ${THIS_GIT_CLONE_PATH}/hostapd.patch
```


