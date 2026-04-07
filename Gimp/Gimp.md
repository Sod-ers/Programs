Edit > Preferences > Tool options > Move tool > Set layer or path as active

| Description:                                        | Resource:                                                                                               |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Make eraser completely erase.                       | https://www.reddit.com/r/GIMP/comments/46u44b/help_just_trying_to_get_the_eraser_tool_to/               |
| How to center a layer.                              | https://imagy.app/how-to-center-a-layer-in-gimp/                                                        |
| Converting color images to B&W.                     | https://www.gimp.org/tutorials/Color2BW/                                                                |
| Use custom path for plugins & Flatseal to allow it. | https://askubuntu.com/questions/1044101/how-to-use-plugins-with-gimp-2-10-flatpak                       |
| Add gradient to text.                               | https://graphicdesign.stackexchange.com/questions/162899/how-do-i-add-gradient-fill-across-text-in-gimp |
| Batch image processing plug-in.                     | https://github.com/kamilburda/batcher                                                                   |
| Resynthesizer Plugin Suite.                         | https://github.com/bootchk/resynthesizer                                                                |

Grocery Images: 300 x 300  
### Troubleshooting:  
  
`bwrap: execvp gimp-3.0: No such file or directory`
When GIMP upgrades, the launch command needs to be updated:  
From:  
`/usr/bin/flatpak run --branch=stable --arch=x86_64 --command=gimp-3.0 --file-forwarding org.gimp.GIMP @@u %U @@`  
To:  
`/usr/bin/flatpak run --branch=stable --arch=x86_64 --command=gimp-3.2 --file-forwarding org.gimp.GIMP @@u %U @@`  
Plugins & Patches will have to be reapplied

### Change Loading Splash Screen:
Add/remove images here: `~/.config/GIMP/3.2/splashes/`

### Install Plugins:
`~/.config/GIMP/3.2/plug-ins/`