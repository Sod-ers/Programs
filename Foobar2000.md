| Resources:                                                                                               |
| -------------------------------------------------------------------------------------------------------- |
| [CaTRoX (QWR Edition)](https://theqwertiest.github.io/CaTRoX_QWR/)                                       |
| [Eole](https://github.com/Ottodix/Eole-foobar-theme)                                                     |
| [footuner](https://github.com/smoralis/footuner)                                                         |
| [Georgia-ReBORN](https://github.com/TT-ReBORN/Georgia-ReBORN)                                            |
| [Icon Collection](https://audio-file.org/2020/01/29/foobar2000-icons-icon-sets/)                         |
| [JAM3 Neumorphism UI](https://www.deviantart.com/ranggakat/art/JAM3-Neumorphism-UI-938250089)            |
| [JAMobile](https://ranggakat.gumroad.com/l/JAMobile)                                                     |
| [MonkeyMote](https://www.monkeymote.com/home)                                                            |
| [My Foobar2000 Configurations](https://drive.google.com/drive/folders/1n4Eag9hu1wwvdgxLzX2sVRkIFSXgFMUC) |
| [NekoRoX](https://github.com/catlinman/foobar2000)                                                       |
| [null2000](https://null-src.com/store/listings/null2000/product.php)                                     |
| [Theme Collection](https://audio-file.org/foobar2000-cui-dui-themes/)                                    |
| [VU Meter Skins Collection](https://audio-file.org/foobar2000-vu-meter-skins-gallery/)                   |

| Pattern:                 | Query Pattern:                                                                              | Sort Pattern: (enable force-sorted.)                                       |
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
| First Listen             | %path% HAS "Z:\First Listen"                                                                | %ALBUM ARTIST% - %DATE% - %ALBUM% - %DISCNUMBER% - %TRACKNUMBER% - %TITLE% |
| Auto Playlists           |                                                                                             | %filename%                                                                 |
| Radio                    | %path% HAS Z:\Radio SORT DESCENDING BY %added%                                              |                                                                            |

| File:                | Directory:                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------ |
| Visualizer color     | ..\profile\configuration\foo_ui_columns.dll.cfg                                            |
| Menu accent color    | ..\profile\foo_spider_monkey_panel\packages\{28AC1EBE-9010-459E-8886-8FFDC8705716}\main.js |
| Volume & title color | ..\profile\configuration\foo_osd.dll.cfg                                                   |

