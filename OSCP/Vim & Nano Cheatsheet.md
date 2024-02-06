

### VIM

- Comprised of *Nodes* (many smaller programs)
- Window is called a *Buffer*
- Practice with `vimtutor` Lib

_Modes_

| **Command** | **Description** |
| ---- | ---- |
| `Normal` | All inputs considered editor commands |
| `Insert` | Insert characters into buffer |
| `Visual` | Highlight, then edit highlighted text |
| `Command` | Enter commands into prompt at the bottom line of buffer, used for sorting, replacing, or deleting |
| `Replace` | Replaces text in specified area |

| **Command** | **Description** |
| ---- | ---- |
| `x` | delete highlighted |
| `i` | insert before |
| `a` | insert after |
| `dw` | delete word |
| `dd` | delete entire line |
| `u` | undo |
| `ctl +r` | redo |
| `p` | paste deleted text |
| `rx` | replace current character with clipboard item |
| `ce` | begin changing word from current position |
| `ctrl +g` | Check which line am I on in file |
| `G` | bottom of file |
| `gg` | top of file |
| `/` | search for phrase |
| `/+n (N)` | next in search, capital for backwards |
| `?` | search above for phrase |
| `:/s/<>/<>` | find and replace (inline) |
| `:/s/<>/<>/g` | find and replace (global) |
| `:!` | run cli command |
| `v` | visual mode (start highlighting) |
| `:r !ls` | inputs result of CLI command into vim file |
| `o` | insert newline below |
| `e` | jump forward a word |
| `y` | copy |
| `:set ic` | ignore cases in operations such as seraching |


### NANO


| **Command** | **Description** |
| ---- | ---- |
| `^` | If you see `^` that stands for "Ctrl" |
| `^T` | Will write CLI command into text within the current nano "pager" |
| `^W` | CTRL+F equivalent, search feature. |
| `^w + ^w + Enter` | Jumps to next found match |
| `^O` | Output/save file |
|  |  |
