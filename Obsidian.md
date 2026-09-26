### Plugins:
| Plugin:                                                                                           | Description:                                                                                                                                          |
| ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Actions URI](https://github.com/czottmann/obsidian-actions-uri)                                  | Adds additional `x-callback-url` endpoints to the app for common actions.                                                                             |
| [Automatic Table of Contents](https://github.com/johansatge/obsidian-automatic-table-of-contents) | Create a table of contents in a note, that updates itself when the note changes.                                                                      |
| [Book Search Plus](https://github.com/curtismchale/obsidian-book-search-plus)                     | Easily create book notes.                                                                                                                             |
| [Calendar](https://github.com/liamcain/obsidian-calendar-plugin)                                  | Calendar widget.                                                                                                                                      |
| [CardBoard](https://github.com/roovo/obsidian-card-board)                                         | Display markdown tasks on kanban-style boards.                                                                                                        |
| [Code Styler](https://github.com/mayurankv/Obsidian-Code-Styler)                                  | Style codeblocks & inline code.                                                                                                                       |
| [Commander](https://github.com/jsmorabito/obsidian-commander)                                     | Add commands to the GUI.                                                                                                                              |
| [Ctrl Click Links](https://github.com/eikowagenknecht/obsidian-ctrl-click-links)                  | Require Ctrl + Click to open links.                                                                                                                   |
| [Daily note creator](https://github.com/mario-holubar/obsidian-daily-note-creator)                | Automatically creates missing daily notes.                                                                                                            |
| [Daily Note Navbar](https://github.com/karstenpedersen/obsidian-daily-note-navbar)                | Adds a bar at the top of daily notes to quickly navigate between them.                                                                                |
| [Dataview](https://github.com/blacksmithgu/obsidian-dataview)                                     | Treat your Obsidian Vault as a database which you can query from.                                                                                     |
| [Duplicate detector](https://github.com/Wishmater/obsidian-plugin-duplicate-detector)             | Highlights duplicate lines in the active open note. Hovering over a highlighted line will show a tooltip with the line number where it is duplicated. |
| [ExcaliBrain](https://github.com/zsviczian/excalibrain)                                           | Graph view to navigate your vault.                                                                                                                    |
| [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)                             | Virtual whiteboard.                                                                                                                                   |
| [File Color](https://github.com/ecustic/obsidian-file-color)                                      | Set colors on folders & files in the file tree.                                                                                                       |
| [File Explorer Count](https://github.com/ozntel/file-explorer-note-count)                         | Provides a file count for folders.                                                                                                                    |
| [Git](https://github.com/Vinzent03/obsidian-git)                                                  | Integrate Git version control with automatic commit-&-sync & other advanced features in Obsidian.md                                                   |
| [Iconic](https://github.com/gfxholo/iconic)                                                       | Customize icons & colors.                                                                                                                             |
| [Journals](https://github.com/srg-kostyrko/obsidian-journal)                                      | Comprehensive journaling solution.                                                                                                                    |
| [Kanban](https://github.com/mgmeyers/obsidian-kanban)                                             | Create markdown-backed Kanban boards.                                                                                                                 |
| [Kanban Bases View](https://github.com/xiwcx/obsidian-bases-kanban)                               | A kanban-style drag-and-drop custom view for Obsidian Bases that allows you to organize your notes into columns based on any property.                |
| [Kindle Highlights](https://github.com/hadynz/obsidian-kindle-plugin)                             | Sync Kindle notes & highlights.                                                                                                                       |
| [Meta Bind](https://github.com/mprojectscode/obsidian-meta-bind-plugin)                           | Make notes interactive with inline input fields, metadata displays, & buttons.                                                                        |
| [Moments](https://github.com/mattmcmanus/obsidian-moments)                                        | Atomic dated entries across all your notes, unified in a dynamic timeline view.                                                                       |
| [Ninja cursor](https://github.com/vrtmrz/ninja-cursor)                                            | Enhance cursor visiblity.                                                                                                                             |
| [Omnisearch](https://github.com/scambier/obsidian-omnisearch)                                     | Search engine that "just works".                                                                                                                      |
| [Print](https://github.com/marijnbent/obsidian-print)                                             | Print your notes directly from Obsidian.                                                                                                              |
| [Query Control](https://github.com/yuanzhixiang/obsidian-query-control)                           | adds controls to embedded queries                                                                                                                     |
| [QuickAdd](https://github.com/chhoumann/quickadd)                                                 | One hotkey to log a line, create a note, or run a whole workflow.                                                                                     |
| [Reminders](https://github.com/uphy/obsidian-reminder)                                            | Adds feature to manage markdown TODOs.                                                                                                                |
| [Remotely Save](https://github.com/remotely-save/remotely-save)                                   | Sync notes between local & cloud with smart conflict.                                                                                                 |
| [Sort and Permute lines](https://github.com/Vinzent03/obsidian-sort-and-permute-lines)            | Sort & Permute lines in whole file or selection.                                                                                                      |
| [Table Sorting](https://github.com/kraibse/obsidian-table-sorting)                                | Organize your tables non-destructively, sorting by multiple columns is supported.                                                                     |
| [Templater](https://github.com/silentvoid13/Templater)                                            | Defines a templating language that lets you insert variables & functions results into your notes.                                                     |
| [Tracker](https://github.com/pyrochlore/obsidian-tracker)                                         | Collect data from notes & represent it comprehensively.                                                                                               |
| [Typewriter Mode](https://github.com/davisriedel/obsidian-typewriter-mode)                        | A distraction-free writing environment.                                                                                                               |
| [Web Clipper](https://obsidian.md/clipper)                                                        | Highlight & capture web pages.                                                                                                                        |

URI examples:  
obsidian://open?vault=Programs\  
obsidian://open?vault=Programs&file=example  
obsidian://vault/Notes/Study/Misc  
https://help.obsidian.md/Extending+Obsidian/Obsidian+URI#Shorthand+formats  
  
Kanban ematrix config:  
`{"kanban-plugin":"board","list-collapse":[false,false,false,false],"show-checkboxes":true,"new-card-insertion-method":"prepend-compact","hide-card-count":false}`  
  
Adjust Kanban lane-width for mobile devices by clicking settings top right; settings stored in `../.obsidian/plugins/obsidian-kanban/data.json`  
  
Tablet width: 602  
  
Disable automatic update checking.  
  
| Description:                 | URL(s):                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Obsidian Eistenhower Matrix. | [https://forum.obsidian.md/t/eisenhower-matrix-kanban-style/77729](https://forum.obsidian.md/t/eisenhower-matrix-kanban-style/77729)  <br>[https://tfthacker.com/eisenhower-matrix-kanban](https://tfthacker.com/eisenhower-matrix-kanban)  <br>[https://help.obsidian.md/snippets](https://help.obsidian.md/snippets)  <br>[https://help.obsidian.md/properties](https://help.obsidian.md/properties)  <br>[https://www.browserstack.com/guide/how-to-use-css-rgba](https://www.browserstack.com/guide/how-to-use-css-rgba) |
  
Use Flatpak to remember window size/position.  
  
### Syncing Obsidian with Nexcloud:
0. Install [Remotely Save](https://github.com/remotely-save/remotely-save) plugin.
1. Enter the settings below, REVIEW COMMENTS:

| Setting:                                    | Value:                                     | Comments:                                                                                                                                                     |
| ------------------------------------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Choose a Remote Service                     | Webdav                                     |                                                                                                                                                               |
| Server Address                              | *                                          | Open Nextcloud dashboard, files, bottom left settings to find server address.                                                                                 |
| Username                                    | *                                          | Nextcloud username.                                                                                                                                           |
| Password                                    | *                                          | Nextcloud password or [generate an app password](https://docs.nextcloud.com/server/stable/admin_manual/configuration_user/authentication.html#app-passwords). |
| Depth Header Sent To Servers                | infinity                                   |                                                                                                                                                               |
| Schedule For Auto Run                       | *                                          | Consider enabling if using desktop & mobile at the same time.                                                                                                 |
| Run Once On Start Up Automatically          | 1 second                                   | ONLY FOR MOBILE.<br><br>DISABLE FOR PC DESKTOP VAULTS THAT ARE ALREADY IN NEXTCLOUD.                                                                          |
| Sync On Save                                | Enable                                     | ONLY FOR MOBILE.<br><br>DISABLE FOR PC DESKTOP VAULTS THAT ARE ALREADY IN NEXTCLOUD.                                                                          |
| Regex Of Paths To Ignore                    | .git<br>.gitignore<br>LICENSE<br>nohup.out | Add files & directories to skip syncing here.                                                                                                                 |
| Sync Config Dir                             | Enable                                     | ONLY FOR MOBILE.<br><br>DISABLE FOR PC DESKTOP VAULTS THAT ARE ALREADY IN NEXTCLOUD.                                                                          |
| Abort Sync If Modification Above Percentage | 100 (disable the protection)               |                                                                                                                                                               |
2. Scroll back up & click "Check Connectivity" button.  
  
**Notes:**  
- Obsidian Vault MUST be a base directory in Nextcloud (example: Nextcloud/Notes  or  Nextcloud/weekly-planner). Symlinks do not work & changing base directory means using a different folder, not changing paths (messes things up).
- Old Android device instability if large vaults exist (supports Android version 5.1+).  
- Disable internet connection on mobile devices to adjust settings, then resolve conflicts (choose newest).  
- [APK download](https://obsidian.md/download).  
  
**Sources:**
[Syncing Obsidian with Nexcloud.](https://rshyn.site/posts/sync-obsidian-with-nextcloud.html)  
[What is/are the correct url(s) for webdav?](https://help.nextcloud.com/t/what-is-are-the-correct-url-s-for-webdav/23061/2)  
  
**Open dev console:**  
Ctrl+Shift+i  
  
**Icons:**  
https://lucide.dev/icons/  
  
**Journal/reading vault setup essential tutorials:**
https://youtu.be/FNALXJ1DQXs  
https://youtu.be/91H_0ii4S-A  
https://youtu.be/3Ev0E-5u5WI  
https://youtu.be/ELhdhdE0vUQ  
https://youtu.be/kW_WPn3nRvQ  
https://youtu.be/yk6gdBUaLbw  
https://youtu.be/2p_ahJnmS6U  
https://youtu.be/JbnFHevDyW4  
https://youtu.be/iw8rTKT2KTo  
https://youtu.be/-h7ZAuuNDLE  
https://youtu.be/v84uSIqqVPQ  
https://youtu.be/P57Bg5yIkdA  
https://youtu.be/MOWFU_sDJpg  
https://forum.obsidian.md/t/dynamic-embedded-link-for-todays-daily-note/68314  
https://forum.obsidian.md/t/sort-all-notes-in-order-of-last-modified-similar-to-keeps/86336/4  
https://gist.github.com/dannberg/48ea2ba3fc0abdf3f219c6ad8bc78eb6 
https://obsidian.md/help/callouts  
https://www.reddit.com/r/ObsidianMD/comments/1qe5ytl/custom_callouthow_to_center_title_vertically_and/  
  