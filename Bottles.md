https://docs.usebottles.com/bottles/programs
### Add programs to your Desktop (Flatpak):

To add a program in your Desktop Applications menu, choose "Add Desktop Entry" in the program's menu.

The Flatpak version need a special permission to generate desktop entries. To achieve this, close Bottles and open your terminal, then type:

```
flatpak override com.usebottles.bottles --user --filesystem=xdg-data/applications
```