### Build on Linux:
1. Install dependencies:  
https://github.com/armory3d/armortools/wiki/Linux-Dependencies/cfbb55bc94dcbfbd5a726f257f7b16e59bc74c7a
Debian/Ubuntu:  
`sudo apt install make clang libxinerama-dev libxrandr-dev libasound2-dev libxi-dev mesa-common-dev libgl-dev libxcursor-dev libvulkan-dev libgtk-3-dev libudev-dev libstdc++-12-dev`  
Fedora/similar:
`sudo dnf install make clang libXinerama-devel libXrandr-devel alsa-lib-devel libXi-devel mesa-libGL-devel libXcursor-devel vulkan-devel gtk3-devel libstdc++-static libudev-devel wayland-protocols-devel`

2. Clone the repo:
`git clone https://github.com/armory3d/armortools.git`

3. Change directory:
`cd armortools/paint/`

4. Compile:
`../base/make --compile`

5. Output complete at:
`armortools/paint/build/out/ArmorPaint` 

6. (Optional) Create .desktop file at ~/.local/share/applications
```
[Desktop Entry]
Name=Armor Paint
Version=1.0
Type=Application
Exec=/opt/armorpaint/ArmorPaint
Icon=/opt/armorpaint/icon.png
```
### Misc Notes:
- Program won't launch if selected theme file is missing.
- Themes colors use `Android / android.graphics.Color` values (https://encycolorpedia.com)