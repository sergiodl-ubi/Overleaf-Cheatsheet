# Overleaf Cheatsheet
Overleaf frequently used commands, functions or shortcuts

I'm writing this document as a cheat sheet for my Master Thesis writing.
It might include commands that only work for my latex template.

## Commands and Functions

### Whitespace and newlines

`\\` (inline, newline)  
`\newpage`  

### Sections

`\section`  
`\subsection`  
`\subsubsection`  

## Keybindings 

### Multiple Selections

Excerpt from [Keybinding for multiple selection in ShareLaTeX?](https://tex.stackexchange.com/questions/551653/keybinding-for-multiple-selection-in-sharelatex):   
The full list of keyboard shortcuts that work for me in Overleaf to create multiple cursors / selections:

* `Ctrl+Alt+Right` (or additionally `Ctrl+Alt+L` in Vim mode): search for next occurence of word under cursor, add it to selection
* `Ctrl+Alt+Left` (or additionally `Ctrl+Alt+H` in Vim mode): search for previous occurence of word under cursor, add it to selection
* `Ctrl+Alt+Down` (or additionally `Ctrl+Alt+J` in Vim mode): add cursor one line below
* `Ctrl+Alt+Up` (or additionally `Ctrl+Alt+K` in Vim mode): add cursor one line above

For these above, hold also Shift to skip items / lines.

* `Ctrl + click somewhere`: add new cursor
* `Alt + click and drag through multiple lines`: block selection, add multiple cursors
* `Ctrl+Alt+K` if keybindings set to None: select all occurences of text under cursor

Furthermore, if using multiple selections with Vim mode, it's good to know that you need to press Shift+A or Shift+I to enter insert mode.
