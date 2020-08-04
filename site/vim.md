| *VI Modes (Switching between)                                              || 
|----------------------|------------------------------------------------------|
| ESC                  | Normal Mode                                          |
| i                    | insert mode   I - beginning of line                  |
| a                    | append        A - at end of the line                 |
| o                    | open a new line below   O - a new line above         |
| v                    | visual mode                                          |


| *Moving In The File*                                              || 
|----------------------|---------------------------------------------|
| h , j , k , l        | h (left)   j (down)   k (up)   l (right)    |
| w                    | to the start of next word                   |
| e                    | to the end of next work                     |
| 0                    | to the beginning of the line                |
| $                    | to the end of the line                      |
| gg                   | to the top of the file                      |
| G                    | to the bottom of the file                   |
| Crtl + g             | displays your location in fil               |
| Ctrl + o             | Return to previous location                 |
| Ctrl + i             | Go forward (Inverse of above command)       |



| *Cut, Copy & Paste*                                               || 
|----------------------|---------------------------------------------|
| Cut                  | d + motion                                  |
| Copy                 | y + motion                                  |
| Paste                | p                                           |

| *Editing*                                                         || 
|----------------------|---------------------------------------------|
| x                    | delete a character                          |
| r                    | replace a character  R - Replace overwrite  |
| dd                   | delete line                                 |
| dw                   | delete work                                 |
| de                   | delete to the end of current word           |
| d0                   | delete to beginning of line                 |
| d$                   | delete to the end of line                   |


| *Change Operator                                                  || 
|----------------------|---------------------------------------------|
| c [number] motion    | change to end of word                       |


| *Undo / Redo*                                                     || 
|----------------------|---------------------------------------------|
| u                    | undo  (U - undo all the changes on a line)  |
| Ctrl + r             | redo                                        |

| *Matching Parentheses Search* ) , } , }                           || 
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
| q!                   | quit without saving                         |
| wq                   | save and quit                               |
| sav filename.txt     | save as                                     |
| e!                   | revert file                                 |

| *Running External BASH Commands*                                  || 
|----------------------|---------------------------------------------|
| ! command            | Executes a single command in BASH shell     |