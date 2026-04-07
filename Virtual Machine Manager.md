Solutions after system upgrade breaking changes:  
  
1. Reinstall `Virtiofsd` package.  
  
Error starting domain: unsupported configuration: chardev 'spicevmc' not supported without spice graphics:  
  
1. View machine details.  
2. Add hardware.  
3. Select graphics (default is Spice server).  
4. Click finish & run machine.  
   
libvirt-guests.sh: Can't connect to default. Skipping.:
1. Open `/usr/lib/libvirt/libvirt-guests.sh` in a text editor as Root.
2. Change the following lines:
from
```
ON_SHUTDOWN="shutdown"
SHUTDOWN_TIMEOUT=300
```
to
```
ON_SHUTDOWN="ignore"
SHUTDOWN_TIMEOUT=1
```
3. Be mindful to shutdown virtual machines or implement your own VM shutdown script; there's plenty.