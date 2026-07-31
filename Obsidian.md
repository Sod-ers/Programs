
| Plugin:                                                                                           | Description:                                                                                                                                          |
| ------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Actions URI](https://github.com/czottmann/obsidian-actions-uri)                                  | Adds additional `x-callback-url` endpoints to the app for common actions.                                                                             |
| [Automatic Table of Contents](https://github.com/johansatge/obsidian-automatic-table-of-contents) | Create a table of contents in a note, that updates itself when the note changes.                                                                      |
| [CardBoard](https://github.com/roovo/obsidian-card-board)                                         | Display markdown tasks on kanban-style boards.                                                                                                        |
| [Ctrl Click Links](https://github.com/eikowagenknecht/obsidian-ctrl-click-links)                  | Require Ctrl + Click to open links.                                                                                                                   |
| [Duplicate detector](https://github.com/Wishmater/obsidian-plugin-duplicate-detector)             | Highlights duplicate lines in the active open note. Hovering over a highlighted line will show a tooltip with the line number where it is duplicated. |
| [ExcaliBrain](https://github.com/zsviczian/excalibrain)                                           | Graph view to navigate your vault.                                                                                                                    |
| [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)                             | Virtual whiteboard.                                                                                                                                   |
| [Git](https://github.com/Vinzent03/obsidian-git)                                                  | Integrate Git version control with automatic commit-&-sync & other advanced features in Obsidian.md                                                   |
| [Kanban](https://github.com/mgmeyers/obsidian-kanban)                                             | Create markdown-backed Kanban boards.                                                                                                                 |
| [Kanban Bases View](https://github.com/xiwcx/obsidian-bases-kanban)                               | A kanban-style drag-and-drop custom view for Obsidian Bases that allows you to organize your notes into columns based on any property.                |
| [Print](https://github.com/marijnbent/obsidian-print)                                             | Print your notes directly from Obsidian.                                                                                                              |
| [Reminders](https://github.com/uphy/obsidian-reminder)                                            | Adds feature to manage markdown TODOs.                                                                                                                |
| [Remotely Save](https://github.com/remotely-save/remotely-save)                                   | Sync notes between local & cloud with smart conflict.                                                                                                 |
| [Sort and Permute lines](https://github.com/Vinzent03/obsidian-sort-and-permute-lines)            | Sort & Permute lines in whole file or selection.                                                                                                      |
| [Table Sorting](https://github.com/kraibse/obsidian-table-sorting)                                | Organize your tables non-destructively, sorting by multiple columns is supported.                                                                     |
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