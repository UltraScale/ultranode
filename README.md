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


Now add the folowing in the file /etc/rc.local
```
sudo mount -t vboxsf -o uid=1000,gid=1000  workbench /home/[username]/workbench
exit 0
```

And don't forget to create the directory ~/workbench and configure automount in the VirtualBox settings

