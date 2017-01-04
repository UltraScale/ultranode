# ultranode
Different RBPi images for running kubernetes and base tools


## Development environment

Ubuntu 16.04 LTS Server

### For Virtualbox intallation: 

**First:**
```
sudo apt-get update
sudo apt-get install build-essential linux-headers-$(uname -r)
``` 

**Then:** Install from the addon CD: ```sudo /media/cdrom/VBoxLinuxAdditions.run```


Add in /etc/fstab:
```
workbench   /workbench   vboxsf   uid=1000,gid=1000,auto,rw  0   0
```

And don't forget to create the directory /workbench with rw acces for all

