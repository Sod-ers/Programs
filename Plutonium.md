### Installing Plutonium on Linux - NVIDIA:
1. Install games; Campaign, Zombies _**and/OR**_ Multiplayer (only install modes you plan to play; don't need all).
2. Make a WINE prefix with DotNET 4.8, D3D Compiler 4.7 & the Microsoft Core Fonts, ignore the errors: `WINEPREFIX=~/.local/share/wineprefixes/cod winetricks dotnet48 d3dcompiler_47 corefonts`
3. Fix sound issues & locked audio device, ignore the errors: `WINEPREFIX=~/.local/share/wineprefixes/cod winetricks faudio xact xaudio2_7 xaudio2_9`
4. Download [Plutonium](https://plutonium.pw/docs/install/) & [Lutris](https://lutris.net/downloads).
5. Pull up Lutris, & click the + on the top left hand corner. After that, select "Add Locally Installed Game".
6. In the "Game Info" tab, select WINE as your runner.
7. On the "Game Options" tab, click the three dots by the Executable text box, & search for where you placed Plutonium. Click "Open", or something similar in your file manager of choice.
8. For your WINE prefix, just select the one you had just made. Leave everything else as default.
9. Once you go into Runner Options, turn on the "Advanced" toggle right by the "Save" button. These upcoming steps require the advanced settings to be turned on.
10. Try different WINE versions. wine-ge-8-26-x86_64 is known good.
11. On the Graphics box, enable everything, and make sure they're at the latest version of each.
12. If your kernel supports it, turn on _**both**_ Esync & Fsync. My kernel does, so I turn both on. If you can only do Esync, that's fine too.
13. Disable AMD FidelityFX Super Resolution (FSR), BattlEye Anti-Cheat, Easy Anti-Cheat.
14. Fill in DLL Overrides values. Check notes if applicable.

| Key:                                | Value:                | Notes:                                     |
| ----------------------------------- | --------------------- | ------------------------------------------ |
| DXVK_STATE_CACHE                    | 1                     | DXVK shaders                               |
| DXVK_STATE_CACHE_PATH               | /path/to/dxvk_cache   | Where DXVK shaders are stored              |
| STAGING_SHARED_MEMORY               | 0                     |                                            |
| WINEESYNC                           | 1                     |                                            |
| WINEFSYNC                           | 1                     | Only if Fsync is supported                 |
| __GL_SHADER_DISK_CACHE              | 1                     | For shader purposes                        |
| __GL_SHADER_DISK_CACHE_PATH         | /path/to/shader_cache | Where shader cache is stored               |
| __GL_SHADER_DISK_CACHE_SKIP_CLEANUP | 1                     | Keep shaders loaded for better performance |
| __GL_THREADED_OPTIMIZATIONS         | 1                     |                                            |
15. Click "System options" tab, turn on "Disable Lutris Runtime". This essentially will disable the Lutris libraries. Likewise, make sure you have the system libraries preferred.
16. Under Display box, disable both desktop effects & screensaver.
17. (Skip on CachyOS) Under CPU box, Enable Feral GameMode if you have the Gamemode daemon by Feral Interactive.
18. (Optional, skip on Pipewire) Under audio box, reduce PulseAudio latency to 60 miliseconds.
19. Under Game execution box, Fill in Environment variables below. Check notes if applicable.

| Key:              | Value:        | Notes:             |
| ----------------- | ------------- | ------------------ |
| WINE_ENABLE_NVAPI | 1             | Required on NVIDIA |
| VK3D_CONFIG       | no_upload_hvv |                    |
20. (CachyOS only) Under Game execution box > Command prefix, you need to put `game-performance`.
21. Save the game, launch it, & log in.
22. Select your game, click the blue "Setup" button, then find where you have the game installed. I create a symlink for each game in `~/.local/share/wineprefixes/cod/drive_c/users/soders/Favorites/` & they appear in WINE Explorers Quick Access favorites.
Notes:  
- WINE prefix size: 2.4 GiB.
- GLCache size: 420.4 MiB (growing?).
- plutonium.exe 4.6 MiB.
  
SOURCES:
https://forum.plutonium.pw/topic/39182/installing-plutonium-on-linux-with-nvidia-gpu-full-guide
https://www.protondb.com/app/42700#hOEbj8TTKj

### Mods directories:
`C:\Users\Name\AppData\Local\Plutonium\storage\t6\scripts\zm`  
`C:\Users\Name\AppData\Local\Plutonium\storage\t6\scripts\mp`  