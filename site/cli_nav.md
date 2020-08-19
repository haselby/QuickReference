Command Line Input - Navigation


**Moving the Cursor**
| BASH               | PowerShell         | Description                                 |
|--------------------|--------------------|---------------------------------------------|
| Ctrl + A           | Home               | Go to the beginning of the line             |
| Ctrl + E           | End                | Go to the end of the line                   |
| Ctrl + →           | Ctrl + →           | Go right one word                           |
| Ctrl + ←           | Ctrl + ←           | Go left one word                            |


**Delete Text**
| BASH               | PowerShell         | Description                                 |
|--------------------|--------------------|---------------------------------------------|
| Ctrl + U           | Ctrl + Home        | Delete from cursor to beginning of the line |
| Alt + K            | Ctrl + End         | Delete from cursor to end of the line       |
| Ctrl + A + K       | Esc                | Delete current line                         |

**Terminal**
| BASH               | PowerShell         | Description                                 |
|--------------------|--------------------|---------------------------------------------|
| Ctrl + L           |  Ctrl + L          | Clear Terminal                              |

**Command History**
| BASH               | PowerShell         | Description                                      |
|--------------------|--------------------|--------------------------------------------------|
| Ctrl + R           |  Ctrl + R          | Search command in history - type the search term |
| Ctrl + R           |  Ctrl + R          | Continue to search future back in history        |

**Delete Command History Surgically**
| BASH               | PowerShell           | Description                           |
|--------------------|----------------------|---------------------------------------|
| history -d  42     | Clear-History -Id 42 | Deletes specific location in history  |

**Clear Command History & Arrow Scroll History**
 
    Bash     history -c && history -w	
    PS       Clear-History; Remove-Item (Get-PSReadlineOption).HistorySavePath    (then  Alt F7)			
		
