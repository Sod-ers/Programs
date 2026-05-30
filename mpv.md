### Keybinds:
**mpv:**

| Key:                 | Command:                          |
| -------------------- | --------------------------------- |
| LEFT                 | playlist-prev                     |
| RIGHT                | playlist-next                     |
| MBTN_LEFT            | playlist-prev                     |
| MBTN_RIGHT           | playlist-next                     |
| SPACE                | cycle pause                       |
| L                    | cycle-values loop-file "inf" "no" |
| l                    | cycle-values loop-file "inf" "no" |
| Up                   | frame-step                        |
| Down                 | frame-back-step                   |
| ENTER                | screenshot                        |
| shift+enter          | screenshot each-frame             |
| Ctrl+Alt+Shift+Left  | seek -3                           |
| Ctrl+Alt+Shift+Right | seek 3                            |
| Ctrl+Alt+Shift+Space | cycle pause                       |
| s                    | cycle sub-visibility              |
| S                    | cycle sub-visibility              |
**mpv-shim:**

| Key:                 | Command:              |
| -------------------- | --------------------- |
| Ctrl+Alt+Shift+Up    | add volume 5          |
| Ctrl+Alt+Shift+Down  | add volume -5         |
| Ctrl+Alt+Shift+Left  | seek  -3              |
| Ctrl+Alt+Shift+Right | seek  3               |
| Ctrl+Alt+Shift+Space | cycle pause           |
| Left                 | frame-back-step       |
| Right                | frame-step            |
| Enter                | screenshot            |
| shift+enter          | screenshot each-frame |
| s                    | cycle sub-visibility  |
| S                    | cycle sub-visibility  |
**mpv-rtsp:**

| Key:  | Command:      |
| ----- | ------------- |
| ENTER | screenshot    |
| 1     | playlist-prev |
| 2     | playlist-next |
| LEFT  | playlist-prev |
| RIGHT | playlist-next |
### Bookmarks:
| Bookmark:                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Manual](https://mpv.io/manual/)                                                                                                                         |
| [builtin.conf (profiles)](https://github.com/mpv-player/mpv/blob/master/etc/builtin.conf)                                                                |
| [Default mpv.conf](https://github.com/mpv-player/mpv/blob/master/etc/mpv.conf)                                                                           |
| [Default input.conf](https://github.com/mpv-player/mpv/blob/master/etc/input.conf)                                                                       |
| [User Scripts wiki](https://github.com/mpv-player/mpv/wiki/User-Scripts)                                                                                 |
| [Restart (not reload) mpv - script](https://gist.github.com/nilninull/64389dcbe7e43bed8df6c9aef914d58e)                                                  |
| [Various scripts for mpv](https://github.com/occivink/mpv-scripts)                                                                                       |
| [Configurations & scripts](https://github.com/noelsimbolon/mpv-config)                                                                                   |
| [mpv keybindings to create Anki cards from movies and TV shows](https://github.com/Ajatt-Tools/mpvacious)                                                |
| [Collection of scripts modified for better language learning experience](https://github.com/wa8eem/mpv-scripts)                                          |
| [Collection of scripts for mpv](https://github.com/CogentRedTester/mpv-scripts)                                                                          |
| [Experimental scripts for mpv](https://github.com/kelciour/mpv-scripts)                                                                                  |
| [mpv scripts](https://github.com/jonniek/mpv-scripts)                                                                                                    |
| [Scripts for mpv](https://github.com/Eisa01/mpv-scripts)                                                                                                 |
| [awesome-mpv](https://github.com/stax76/awesome-mpv)                                                                                                     |
| [mpv-reload](https://github.com/4e6/mpv-reload)                                                                                                          |
| [mpv.net skin](https://github.com/mpvnet-player/mpv.net)                                                                                                 |
| [ModernZ skin](https://github.com/Samillion/ModernZ)                                                                                                     |
| [A beginner's guide to customizing your media player](https://www.reddit.com/r/mpv/comments/11ytoue/a_beginners_guide_to_customizing_your_media_player/) |
| [mpv best settings/more configs](https://www.reddit.com/r/mpv/comments/1jhuoip/please_help_me_with_my_mpv_settings_for_the_best/)                        |
| [Tutorials](https://thewiki.moe/tutorials/mpv/)                                                                                                          |
| [ModernX](https://github.com/cyl0/ModernX)                                                                                                               |
| [ModernX fork](https://github.com/zydezu/ModernX)                                                                                                        |
| [Windows builds](https://github.com/zhongfly/mpv-winbuild)                                                                                               |
| [Configuration for Windows](https://github.com/Zabooby/mpv-config)                                                                                       |
| [Shaders](https://github.com/iwalton3/default-shader-pack)                                                                                               |
| [ff2mpv](https://github.com/woodruffw/ff2mpv)                                                                                                            |
| [Plex HTPC-Inspired theme](https://github.com/LitCastVlog/MPV-Plex-Inspired-OSC-Theme)                                                                   |
| [thumbfast](https://github.com/po5/thumbfast)                                                                                                            |
| [BoxToWide](https://github.com/Samillion/mpv-boxtowide)                                                                                                  |
| [remember-volume.lua](https://gist.github.com/blackarcher21/162dc1bef708e90082c6c4f9500c1997)                                                            |
| [mpv gif generator script](https://github.com/DanSM-5/mpv-gif-generator)                                                                                 |
| [Audio visualizer script](https://github.com/mfcc64/mpv-scripts/blob/master/visualizer.lua)                                                              |
### Misc:
- `vo=gpu-next` requires `gpu-api=vulkan` for screenshots to work; fails with `gpu-api=opengl`.
- `--config-dir="/home/soders/.var/app/com.github.iwalton3.jellyfin-mpv-shim/config/jellyfin-mpv-shim/"`
