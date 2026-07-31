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

# Edit Prime settings after first reboot, then reboot again to fix panels.
```
Although driver manager claims Nouveau is in use, Terminal reports Nvidia:  
```
lsmod | grep -E "(nvidia|nouveau)"

cat /proc/driver/nvidia/version

inxi -Gx
```
Reboot twice to fix monitor/panel names.  
Update Flatpak afterwards to fix "No available configurations for the given pixel format" error.  
  
### The difference between metapackage & open kernel drivers:  
https://ubuntu-mate.community/t/open-kernel-drivers-and-metapackage-tested/31058/2  
  
Metapackages: A collection of packages to install, meant for older GPUs.  
Open Kernel: Drivers with community contributions, meant for modern GPUs.  
  
Whether or not the Nvidia driver & Kernel modules will work with a specific kernel version is based on how their installation is handled.  
  
### Changelogs:  
https://github.com/NVIDIA/open-gpu-kernel-modules/releases  
  
### Misc:  
[Troubleshooting NVIDIA driver issues after Kernel update on Ubuntu.](https://oneuptime.com/blog/post/2026-03-02-how-to-troubleshoot-nvidia-driver-issues-after-kernel-update-on-ubuntu/view)  
