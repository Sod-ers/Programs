### Ensure Nvidia drivers load during boot & all settings available:  
1. Add  
```
nvidia
nvidia-modeset
nvidia-drm
```
to  
`/etc/initramfs-tools/modules`

2. Run `sudo update-initramfs -u  
   
3. Reboot.  
   
Source:  
https://forums.linuxmint.com/viewtopic.php?t=341144  
### Switch/remove Nvidia drivers:  
```
sudo apt update

sudo apt purge nvidia-* libnvidia-*

sudo apt autoremove

sudo apt install nvidia-driver-580  # Replace with desired version

sudo update-initramfs -u

# grub customizer refresh & save

sudo reboot
```
Although driver manager claims Nouveau is in use, Terminal reports Nvidia:  
```
lsmod | grep -E "(nvidia|nouveau)"

cat /proc/driver/nvidia/version

inxi -Gx
```
Reboot twice to fix monitor/panel names.  