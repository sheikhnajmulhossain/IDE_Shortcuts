# Visual Studio Code Keyboard Shortcuts for Windows

Here’s a handy reference image with most of the common shortcuts:

![VS Code Shortcuts Reference](./vscode_shortcuts_windows.png "VS Code Shortcuts")

Below is a textual version of those shortcuts in table form, which you can copy or adapt as needed.

---

## General
| Shortcut                   | Action / Command            | Description                                       |
| -------------------------: | :-------------------------- | :------------------------------------------------ |
| **Ctrl + Shift + P**, **F1** | Show Command Palette       | Open quick actions and commands                   |
| **Ctrl + P**                | Quick Open (Go to File)     | Quickly open files in the workspace              |
| **Ctrl + Shift + N**        | New window / instance       | Open a new VS Code window                         |
| **Ctrl + Shift + W**        | Close window / instance     | Close the current VS Code window                  |
| **Ctrl + K**, **Ctrl + S**  | Keyboard Shortcuts          | View and customize keyboard shortcuts             |

---

## Basic Editing
| Shortcut                 | Action / Command            | Description                                             |
| -----------------------: | :-------------------------- | :------------------------------------------------------ |
| **Ctrl + X**             | Cut line (no selection)     | Cuts entire line if nothing is selected                |
| **Ctrl + C**             | Copy line (no selection)    | Copies entire line if nothing is selected              |
| **Alt + ↑ / ↓**          | Move line up/down           | Moves current line or selection up/down                |
| **Shift + Alt + ↑ / ↓**  | Copy line up/down           | Copies current line or selection up/down               |
| **Ctrl + Shift + K**     | Delete line                 | Deletes entire current line                            |
| **Ctrl + Enter**         | Insert line below           | Inserts a new line below the current line              |
| **Ctrl + Shift + Enter** | Insert line above           | Inserts a new line above the current line              |
| **Ctrl + ] / [**         | Indent / outdent line       | Moves line text right or left                          |
| **Ctrl + Home / End**    | Go to file start/end        | Moves cursor to start/end of file                      |
| **Home / End**           | Go to line start/end        | Moves cursor to start/end of the line                  |
| **Ctrl + ↑ / ↓**         | Scroll line up/down         | Scrolls editor view without moving cursor              |
| **Ctrl + PgUp / PgDn**   | Scroll page up/down         | Scrolls by full page in the editor                     |
| **Ctrl + /**             | Toggle line comment         | Comments/uncomments current line/selection             |
| **Ctrl + K**, **Ctrl + C** | Add line comment            | Adds comment to current line/selection              |
| **Ctrl + K**, **Ctrl + U** | Remove line comment         | Removes comment from current line/selection         |
| **Alt + Z**              | Toggle word wrap            | Wraps text to fit editor width                         |

---

## Navigation
| Shortcut             | Action / Command                   | Description                                               |
| -------------------: | :--------------------------------- | :-------------------------------------------------------- |
| **Ctrl + T**         | Show all symbols                   | Lists all symbols in the workspace                        |
| **Ctrl + G**         | Go to line…                        | Jumps to a specific line number                           |
| **Ctrl + P**         | Quick Open (Go to File)            | Quickly open files in the workspace                       |
| **Ctrl + Shift + O** | Go to symbol in file…              | Jump to symbols in the current file                       |
| **Ctrl + Shift + M** | Show Problems panel                | Displays problems (errors, warnings) panel               |
| **F8 / Shift + F8**  | Next / previous error or warning   | Jumps to next/previous error or warning                  |
| **Ctrl + Shift + Tab** | Navigate editor group history    | Cycles through previously opened editors in a group       |
| **Alt + ← / →**      | Go back / forward                  | Moves backward/forward in navigation history             |

---

## Search and Replace
| Shortcut            | Action / Command                | Description                                                |
| ------------------: | :------------------------------ | :--------------------------------------------------------- |
| **Ctrl + F**        | Find                            | Searches text in the current file                          |
| **Ctrl + H**        | Replace                         | Replaces text in the current file                          |
| **F3 / Shift + F3** | Find next / previous            | Moves to next/previous search match                        |
| **Alt + Enter**     | Select all occurrences of match | Highlights all matches of the current search               |
| **Ctrl + D**        | Add selection to next find match| Repeats selection for the next match                       |
| **Ctrl + K**, **Ctrl + D** | Move last selection to next | Skips current match and selects the next match         |
| **Alt + C / R / W** | Toggle case-sensitive / regex / whole word | Adjusts find/replace options                 |

---

## Multi-Cursor & Selection
| Shortcut                       | Action / Command                             | Description                                          |
| -----------------------------: | :------------------------------------------ | :--------------------------------------------------- |
| **Alt + Click**               | Insert cursor at clicked location           | Adds a new cursor wherever you click                 |
| **Ctrl + Alt + ↑ / ↓**        | Insert cursor above/below                   | Adds additional cursors above/below current line     |
| **Ctrl + U**                  | Undo last cursor operation                  | Removes the most recent multi-cursor                 |
| **Shift + Alt + I**           | Insert cursor at end of each selected line  | Places a cursor at end of every selected line        |
| **Ctrl + I**                  | Select current line                         | Highlights the entire current line                   |
| **Ctrl + Shift + L**          | Select all occurrences of selection         | Highlights all matches of your current selection     |
| **Ctrl + F2**                 | Select all occurrences of current word      | Highlights all instances of the word under cursor    |
| **Shift + Alt + → / ←**       | Expand / shrink selection                   | Extends or shrinks selection by word/character       |
| **Ctrl + Shift + Alt + ↑ / ↓**| Column (box) selection                      | Creates a rectangular selection with multiple cursors|

---

## File Management
| Shortcut                               | Action / Command              | Description                                          |
| -------------------------------------: | :---------------------------- | :--------------------------------------------------- |
| **Ctrl + N**                           | New File                      | Creates a new file                                  |
| **Ctrl + O**                           | Open File…                    | Opens file browser prompt                           |
| **Ctrl + S**                           | Save File                     | Saves current file                                  |
| **Ctrl + Shift + S**                   | Save As…                      | Saves current file under new name                   |
| **Ctrl + K**, **S**                    | Save All                      | Saves all open files                                |
| **Ctrl + W**, **Ctrl + F4**            | Close Editor                  | Closes the current file/tab                         |
| **Ctrl + K**, **Ctrl + W**             | Close All Editors             | Closes all open files/tabs                         |
| **Ctrl + Shift + T**                   | Reopen closed editor          | Reopens the last closed editor/tab                  |
| **Ctrl + K**, **Enter**                | Keep preview mode editor open | Pins the current preview editor                    |
| **Ctrl + Tab / Ctrl + Shift + Tab**    | Next / previous open file     | Cycles through open files/tabs                     |
| **Ctrl + K**, **R**                    | Reveal active file in Explorer| Highlights current file in Explorer panel          |
| **Ctrl + K**, **O**                    | Open file in new window       | Opens current file in a new VS Code window          |

---

## Display
| Shortcut               | Action / Command                          | Description                                        |
| ---------------------: | :---------------------------------------- | :------------------------------------------------- |
| **F11**               | Toggle full screen                         | Enters or exits full-screen mode                  |
| **Shift + Alt + 0**   | Toggle editor layout (horizontal/vertical) | Splits layout horizontally or vertically          |
| **Ctrl + = / Ctrl -** | Zoom in / zoom out                         | Changes editor zoom level                         |
| **Ctrl + B**          | Toggle sidebar visibility                  | Shows/hides the sidebar                           |
| **Ctrl + Shift + E**  | Show Explorer / Toggle focus               | Opens the Explorer or toggles focus to it         |
| **Ctrl + Shift + G**  | Show Source Control                        | Opens Git/Source Control view                     |
| **Ctrl + Shift + D**  | Show Debug                                 | Opens Debug view                                  |
| **Ctrl + Shift + X**  | Show Extensions                            | Opens Extensions panel                            |
| **Ctrl + Shift + H**  | Replace in files                           | Opens global find/replace panel                   |
| **Ctrl + Shift + J**  | Toggle search details                      | Expands search details                            |
| **Ctrl + Shift + U**  | Show Output panel                
