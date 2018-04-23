- Show shortcuts : CTRL (K, S) (keep CTRL pressed while hitting K then S)
- Open Command Palette : F1 (or CTRL + P)
- Show/Hide left bar : CTRL + B 
- New instance of VS Code : CTRL + SHIFT + N

## Switch focus between editor and integrated terminal
- Open keyboard shortcuts (CTRL+K CTRL+S)
- Click on the link "keybindings.json" at the top of the page
- Add the lines below 
- Doing so, under Windows, you can then open a terminal with CTRL+ù. Later on, you switch back and forth between the editor and the terminal with the same keyboard shortcut.
```
// Placez vos combinaisons de touches dans ce fichier pour remplacer les valeurs par défaut
[
  { "key": "ctrl+oem_3", 
    "command": "workbench.action.terminal.focus"
  },
  { "key": "ctrl+oem_3", 
    "command": "workbench.action.focusActiveEditorGroup", 
    "when": "terminalFocus"
  }  
]
```
## Multi cursors
- Ctrl + Alt + Down to add a cursor below
- ESC to exit the mode

## C/C++
- Format C++ code (C/C++ extension must be insalled) : ALT + SHIFT + F
- Comment a line   : put the cursor on the line then CTRL (K, C)
- Uncomment a line : put the cursor on the line then CTRL (K, U)
- Comment multiple lines : Select the lines then CTRL (K, C)
- Peek definition Alt F12
- Goto definition F12
- Search symbol ??
- Wrap lines (see Rewrap plugin, 80 col) : ALT + Q

## Line
- Cut, copy, delete a line : CTRL + C, CTRL + V, CTRL + X. No need to select the line. Just put the cursor somewhere on the line
- Move a line up and down  : Alt + Up, Alt + Down
- Copy a line up or down   : Shift + Alt + Up, Shift + Alt + Down
- Move a selected block of lines up and down : Alt + Up, Alt + Down

## Left bar
- CTRL + B
- CTRL + SHIFT + E : Explorer
- CTRL + SHIFT + F : Find
- CTRL + SHIFT + G : Git
- CTRL + SHIFT + D : Debug
- CTRL + SHIFT + X : Extensions

## Markdown - sync view
CTRL K, V (press CTRL + K then V alone)

## File
- Open file CTRL P
- Close file CTRL W
- Navigate amongs files : CTRL + Tab

## Various
- Display console : CTRL ù
- Undo : CTRL + Z
- Undo last undo : CTRL SHIFT Z
- Cursor, next word : CTRL + Left, CTRL + Right
