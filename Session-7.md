# File editor in linux-
- Editors are used to create new files, and edit or modify the content inside it.
- Simply editors are used to read and write data in existing or newly created file.
- Editors can be classified on the basis of interfaces that they use, i.e. Graphical Editors and Command Line Editors. 
## Graphical editor: 
- Graphical editor uses graphical user interface.
- It is easy to use but consumes more memory than command line editors.
- In Linux, following are some well-known graphical editors, 
### 1. gedit: -
- It is same as that of notepad in windows.
- You can open gedit graphically in application menu and also using command as $gedit. 

### 2. kedit: -
- It is similar to gedit but contain some advance features.
-  Generally, we have to install kedit separately to use it. 

### 3. Open office: - 
- Open Office is same as that of MS Office.
- This Open Office is specially developed for Linux based operating systems.
## Command line editor: 
- Command line editor uses command line interface.
- These editors are much faster and consumes less memory than any graphical editors.
- Following are some well-known command line editors:
### 1. nano: - 
- nano editor is easy to use since it provides simple features to edit data from files.
- Syntax- 
nano [filename].[extension] 
### 2. vi and vim: -
- vi (virtual interface) and vim (virtual interface modified) are most commonly used editors.
- vi and vim both editors are same where as vim is the advance version of vi editor.
- Thus, it contains some additional features. These editors works in four different modes, 
* Insert mode 
* Ex-mode 
* Command mode 
* Visual mode
- Syntax- 
* vim [filename]  
### Command Mode-
- this is default mode. Press esc to exit from any mode and enter into command mode.

  
| Command | Description |
|---------|-------------|
| `dd` | Delete current line. |
| `<n>dd` | Delete `<n>` lines from the current line. |
| `dw` | Delete from the current cursor position to the end of the current word. |
| `<n>dw` | Delete `<n>` words from the current cursor position. |
| `yy` | Yank (copy) current line. |
| `<n>yy` | Yank `<n>` lines starting from the current line. |
| `yw` | Yank current word. |
| `<n>yw` | Yank `<n>` words starting from the current word. |
| `cc` | Cut current line and enter insert mode. |
| `<n>cc` | Cut `<n>` lines and enter insert mode. |
| `cw` | Cut from the current cursor position to the end of the current word and enter insert mode. |
| `<n>cw` | Cut `<n>` words starting from the current cursor position and enter insert mode. |
| `p` | Paste the last yanked or deleted text after the cursor position. |
| `s` | Remove current character and enter insert mode. |
| `S` | Remove current line and enter insert mode. |
| `u` | Undo the last change. |
| `Ctrl+r` | Redo the last undone change. |
| `H` | Move cursor to the top line of the screen. |
| `M` | Move cursor to the middle line of the screen. |
| `L` | Move cursor to the bottom line of the screen. |
| `G` | Move cursor to the end of the file. |
| `gg` | Move cursor to the beginning of the file. |
| `<n>gg` | Move cursor to line `<n>` in the file. |
| `/<word>` | Search for `<word>` in the file. |
| `n` | Move to the next occurrence of the search result. |
| `N` | Move to the previous occurrence of the search result. |

### Insert Mode-
- you can actually insert or edit text. 
### Ex-mode-
- special executing mode.
- Use ‘:’ to enter into ex-mode. 
### Visual Mode- 
- this mode is used for selection.
- this mode allows you to select and manipulate text.
- you can enter Visual mode by pressing ‘v’ From Visual mode, you can then perform operations like copying, cutting, or replacing the selected text.
### Ex-mode-
- special executing mode 
* :q 	quit without saving
* :w 	save and stay in file
* :wq or :x 	save and quit
* :q! 	quit without saving forcefully
* :wq! 	save and quit forcefully
* :/<word>   Highlight word/string/character
* :%s/<old>/<new>/g Find and replace old word with new word

### Visual Mode-
- this mode is used for selection. 
* v - Select character by character 	
* V - Select line by line 	
* ctrl+v - Select block 	
* y,d,c - for copy, delete, and cut selected area 	



	

 






