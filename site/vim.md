| *VI Modes (Switching Between)                                              || 
|----------------------|------------------------------------------------------|
| ESC                  | normal mode                                          |
| i                    | insert mode   I - beginning of line                  |
| a                    | append        A - at end of the line                 |
| R                    | replace mode (overwrite)                             |
| o                    | open a new line below   O - a new line above         |
| v                    | visual mode                                          |
| ctrl + v             | visual block mode                                    |
| shift + v            | visual line mode                                     |


| *Moving In The File*                                              || 
|----------------------|---------------------------------------------|
| h , j , k , l        | h (left)   j (down)   k (up)   l (right)    |
| w                    | to the start of next word                   |
| e                    | to the end of next word                     |
| 0                    | to the beginning of the line                |
| $                    | to the end of the line                      |
| gg                   | to the top of the file                      |
| G                    | to the bottom of the file                   |
| :50                  | go to line 50                               |
| Crtl + g             | displays your location in file              |
| Ctrl + o             | Return to previous location                 |
| Ctrl + i             | Go forward (Inverse of above command)       |


| *Cut, Copy & Paste*                                               || 
|----------------------|---------------------------------------------|
| Cut                  | d + motion                                  |
| Cut entire line      | dd
| Copy                 | y + motion                                  |
| Copy entire line     | yy                                          |
| Paste                | p (below)  P (above)                        |


| *Editing*                                                         || 
|----------------------|---------------------------------------------|
| x                    | delete a character                          |
| r                    | replace a character                         |
| dd                   | delete line                                 |
| dw                   | delete word                                 |
| de                   | delete to the end of current word           |
| d0                   | delete to beginning of line                 |
| d$                   | delete to the end of line  (D)              |
| dtc                  | delete up to character c                    |


| *Change Operator                                                  || 
|----------------------|---------------------------------------------|
| c [number] motion    | change                                      |


| Repeat                                                            || 
|----------------------|---------------------------------------------|
| .                    | Repeat last change or command               |            


| *Undo / Redo*                                                     || 
|----------------------|---------------------------------------------|
| u                    | undo  (U - undo all the changes on a line)  |
| Ctrl + r             | redo                                        |


| *Matching Parentheses Search* ) , ] , }                           || 
|----------------------|---------------------------------------------|
| %                    | move to matching bracket                    |


| *Search / Replace*                                                || 
|----------------------|---------------------------------------------|
| /                    | Search                                      |
| ?                    | Search (Reverse Direction)                  |
| *                    | Search for word under the cursor            |
| s/old/new/g          | Replace global                              |
| s/old/new            | Replace next instance                       |


| *File commands*                                                   || 
|----------------------|---------------------------------------------|
| n filename.txt       | create a new file in existing vim session   |
| e filename.txt       | open file                                   |
| e!                   | revert file                                 |
| q!                   | quit without saving                         |
| wq                   | save and quit                               |
| w filename.txt       | save as                                     |
| r filename.txt       | retrieve file and inserts in line below     |  


| *Working With Multiple Files*                                       || 
|------------------------|---------------------------------------------|
| vim -p file1.c file2.c | open two file in vim                        |
| tabnew                 | open a new file in a tab                    |
| tabe file3.c           | add a file to current vim session in a tab  |
| tabn                   | next tab                                    |
| tabp                   | previous tab                                |
| args                   | display filename of current file            |


| *Add Comments To Multiple Lines*                                        || 
|------------------------|---------------------------------------------|
| ctrl + v               | Step 1 "visual block mode"                  |
| j                      | Step 2 "add additional lines                |
| shift + i              | Step 3 "insert at start"                    |
| //                     | Step 4 "type comment characters"            |
| ESC                    | Step 5  "apply to selected lines"           |


| *Remove Comments From Multiple Lines*                               || 
|------------------------|---------------------------------------------|
| ctrl + v               | Step 1 "visual block mode"                  |
| j, h                   | Step 2 "select comments"                    |
| d                      | Step 3 "delete selection"                   |

| *Relocating Multiple Lines*                                         || 
|------------------------|---------------------------------------------|
| shift + v              | Step 1 "visual line mode"                   |
| j                      | Step 2 "select additional lines"            |
| d                      | Step 3 "delete (aka cut) lines"             |
| move to new location   | Step 4 "move to new location"               |
| p                      | Step 5 "paste lines"

| *Recording and Running Macros*                                    || 
|----------------------|---------------------------------------------|
| qa make change q     | record mactro named a                       |
| @a                   | play macro named a                          |

| *Running External BASH Commands*                                  || 
|----------------------|---------------------------------------------|
| ! command            | Executes a single command in BASH shell     |

| *Terminal: Method - Suspend And Resume*                           || 
|----------------------|---------------------------------------------|
| ctrl + z             | suspend vim                                 |
| fg                   | resume vim                                  |
| shell                | launch temporary bash shell                 |
| exit                 | exit temporary bash shell                   |


| *Terminal: Method - In VIM Window*                                || 
|----------------------|---------------------------------------------|
| term                 | launch shell in vim window                  |
| exit                 | exit bash shell in vim window               |
| ctrl + w  direction  | switch active windows using h, j, k, l      |
| resize +5            | increase current window by 5 rows           |



| *Set VIM Options*                                                      || 
|----------------------|--------------------------------------------------|
| set hlsearch         | highlight all matching phrases  (set nohlsearch) |
| set number           | enable line number              (set no number)  |
| syntax on            | enable syntax highlighting      (syntax off)     |
| set tabstop=4        | set tab = 4 spaces              (set ts=4)       |
| set expandtab        | sets vim to replace tabs with spaces             |
| set splitbelow       | open terminal at bottom                          |

