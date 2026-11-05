#HELP!

## NVIM Commands

### General

- u undo
- ctrl r redo

### Explorer (Snacks)
- a add file or directory (directory tails with /)
- r rename
- d delete
- m move
- c copy
- y yank, then p paste
- . focus the explorer on the current directory
- u refresh

- Z closes all folders inside root directory
- . make the selected folder the explorer root

### tabs
 - <leader> tab ] or [
 - gt go to next tab

### Buffer commands
- gg jumps to the first line
- G jumps to the last line
- { } jumps between paragraphs

- % jump between opening closing tags (using vim-matchup) 

### Terminal
open terminal below ctrl + /
open terminal below window at project directory = <leader> - ft
open terminal below window at current directory = <leader> - fT

### Code
toggle show Type popover - K
Go to definition - gd
Go to declaration - gD

### Text Objects
delete using Text Objects. Replace symbol with others, (, [, {, <, '
- di" deletes text inside quotation marks when cursor is IN
- da" deletes text AROUND the quotation marks
- ci" deletes inside and drops you into insert mode ready for you to replace text.
*this works with yank too, prefix symbol with y*

## Tmux Commands
- z zooms current active window and returns to normal view
