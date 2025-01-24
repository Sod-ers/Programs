
```table-of-contents
```
### Resources:
| Resource:                                                                                                |
| -------------------------------------------------------------------------------------------------------- |
| [My foobar2000 Configurations](https://drive.google.com/drive/folders/1n4Eag9hu1wwvdgxLzX2sVRkIFSXgFMUC) |
| [VU Meter Skins Collection](https://audio-file.org/foobar2000-vu-meter-skins-gallery/)                   |
| [Icon Collection](https://audio-file.org/2020/01/29/foobar2000-icons-icon-sets/)                         |
### Themes:
| Theme:                                                                                        |
| --------------------------------------------------------------------------------------------- |
| [CaTRoX (QWR Edition)](https://theqwertiest.github.io/CaTRoX_QWR/)                            |
| [Georgia-ReBORN](https://github.com/TT-ReBORN/Georgia-ReBORN)                                 |
| [Tweaked Tedgo's Darkone](https://www.youtube.com/channel/UCW1YHY2D4DlE7hD3oXSTZRg)           |
| [footuner](https://github.com/smoralis/footuner)                                              |
| [Eole](https://github.com/Ottodix/Eole-foobar-theme)                                          |
| [JAM3 Neumorphism UI](https://www.deviantart.com/ranggakat/art/JAM3-Neumorphism-UI-938250089) |
| [JAMobile](https://ranggakat.gumroad.com/l/JAMobile)                                          |
| [NekoRoX](https://github.com/catlinman/foobar2000)                                            |
| [null2000](https://null-src.com/store/listings/null2000/product.php)                          |
| [Theme Collection](https://audio-file.org/foobar2000-cui-dui-themes/)                         |
### Sort Patterns:
| Pattern:                 | Query Pattern:                                                                              | Sort Pattern: (enable Force-sorted)                                        |
| ------------------------ | ------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Favorites                | %rating% PRESENT AND %rating% IS 5                                                          | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| Songs                    | %path% HAS Z:\Songs\                                                                        | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| Recently Added (Songs)   | %path% HAS Z:\Songs\ AND %added% DURING LAST 1 WEEK SORT DESCENDING BY %added%              |                                                                            |
| Recently Added (Albums)  | %path% HAS Z:\Albums\ AND %added% DURING LAST 1 WEEK SORT DESCENDING BY %added%             | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| Recently Played (Songs)  | %path% HAS Z:\Songs\ AND %last_played% DURING LAST 1 WEEK SORT DESCENDING BY %last_played%  |                                                                            |
| Recently Played (Albums) | %path% HAS Z:\Albums\ AND %last_played% DURING LAST 1 WEEK SORT DESCENDING BY %last_played% |                                                                            |
| Played Often (Songs)     | %path% HAS Z:\Songs\ AND %play_count% GREATER 10 SORT DESCENDING BY %play_count%            |                                                                            |
| Played Often (Albums)    | %path% HAS Z:\Albums\ AND %play_count% GREATER 10 SORT DESCENDING BY %play_count%           |                                                                            |
| 3-4 Stars                | %rating% PRESENT AND %rating% GREATER 2 AND %rating% LESS 5                                 | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| First Listen             | %path% HAS "Z:\First Listen\"                                                               | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| Playlists                |                                                                                             | %filename%                                                                 |
| Radio                    | %path% HAS Z:\Radio\ SORT DESCENDING BY %added%                                             |                                                                            |
### Notable Files:
| File:                | Directory:                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------ |
| Visualizer color     | ..\profile\configuration\foo_ui_columns.dll.cfg                                            |
| Menu accent color    | ..\profile\foo_spider_monkey_panel\packages\{28AC1EBE-9010-459E-8886-8FFDC8705716}\main.js |
| Volume & title color | ..\profile\configuration\foo_osd.dll.cfg                                                   |
### Components:
| Component:                                                                                                          | Description:                                                                                                                                                                |
| ------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Component Collection](https://audio-file.org/foobar2000-list-of-components/)                                       | 478 Components, sorted alphabetically.                                                                                                                                      |
| [MonkeyMote](https://www.monkeymote.com/home)                                                                       | Remote control foobar2000 from your phone.                                                                                                                                  |
| [foo_beefweb](https://www.foobar2000.org/components/view/foo_beefweb)                                               | Provides web interface & REST-like API for controlling player remotely.                                                                                                     |
| [foo_discord_rich](https://www.foobar2000.org/components/view/foo_discord_rich)                                     | Displays information about currently played track via Discord Rich Presence.                                                                                                |
| [foo_dsp_sqracf](https://www.foobar2000.org/components/view/foo_dsp_sqracf)                                         | Smart-crossfade 2 tracks.                                                                                                                                                   |
| [foo_dsp_xgeq](https://www.foobar2000.org/components/view/foo_dsp_xgeq)                                             | Graphic equalizer.                                                                                                                                                          |
| [foo_external_tags](https://www.foobar2000.org/components/view/foo_external_tags)                                   | Adds tagging support for non-taggable file formats.                                                                                                                         |
| [foo_jesus](https://www.foobar2000.org/components/view/foo_jesus)                                                   | Periodic automatic saving of configuration & other data in foobar2000 & keeping backup copies of such data.                                                                 |
| [foo_musicbrainz](https://www.foobar2000.org/components/view/foo_musicbrainz)                                       | Allows tagging files using data from MusicBrainz.                                                                                                                           |
| [foo_openlyrics](https://www.foobar2000.org/components/view/foo_openlyrics)                                         | An open-source lyrics plugin that includes its own UI panel for displaying timed & untimed lyrics as well as sources for downloading lyrics that are not available locally. |
| [foo_osd](https://www.foobar2000.org/components/view/foo_osd)                                                       | Provides configurable screen overlays which may be opened with hotkeys, or appear on specific events.                                                                       |
| [foo_out_asio](https://www.foobar2000.org/components/view/foo_out_asio)                                             | Provides ASIO output support.                                                                                                                                               |
| [foo_out_upnp](https://www.foobar2000.org/components/view/foo_out_upnp)                                             | Presents any UPnP MediaRenderer devices present on your home network as foobar2000 output devices.                                                                          |
| [foo_out_wasapi](https://www.foobar2000.org/components/view/foo_out_wasapi)                                         | Adds Windows Audio Session API exclusive mode output support, allowing bit-exact output & muting all other sounds.                                                          |
| [foo_play_next](https://www.foobar2000.org/components/view/foo_play_next)                                           | Adds the selected track to the beginning of the playback queue to be played next.                                                                                           |
| [foo_playcount](https://www.foobar2000.org/components/view/foo_playcount)                                           | Collects & maintains statistics for played songs.                                                                                                                           |
| [foo_playlist_attributes](https://www.foobar2000.org/components/view/foo_playlist_attributes)                       | Provides support for assigning various attributes to a playlist.                                                                                                            |
| [foo_playlist_revive](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Playlist_Revive_(foo_playlist_revive)) | Makes dead items in a playlist alive again by replacing them with the matching ones in media library.                                                                       |
| [foo_ramdisk](https://www.foobar2000.org/components/view/foo_ramdisk)                                               | Creates temporary copies of a group of tracks in application's memory.                                                                                                      |
| [foo_runcmd](https://www.foobar2000.org/components/view/foo_runcmd)                                                 | Finds & executes menu commands.                                                                                                                                             |
| [foo_skip](https://www.foobar2000.org/components/view/foo_skip)                                                     | Allows skipping tracks that match a specified search query.                                                                                                                 |
| [foo_spider_monkey_panel](https://github.com/TheQwertiest/foo_spider_monkey_panel)                                  | Allows use of JavaScript to create CUI/DUI panels.                                                                                                                          |
| [foo_tags](https://www.foobar2000.org/components/view/foo_tags)                                                     | Support for m-TAGS metadata separation (whereby tags are kept in separate files).                                                                                           |
| [foo_texttools](https://www.foobar2000.org/components/view/foo_texttools)                                           | Customizable context menu commands for copying information about the selected tracks to Windows Clipboard.                                                                  |
| [foo_ui_columns](https://www.foobar2000.org/components/view/foo_ui_columns)                                         | Alternative user interface.                                                                                                                                                 |
| [foo_youtube](https://www.foobar2000.org/components/view/foo_youtube)                                               | Play Youtube videos & playlists directly by their URL.                                                                                                                      |
### Misc:

```
$if($strstr(%path%,'://'),C:\User\Soders\Tags\%album%.png)
```
