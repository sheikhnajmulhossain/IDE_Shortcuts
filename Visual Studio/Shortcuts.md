# VS Code Keyboard Shortcuts

## 1) General
| Shortcut              | Command/Action            | Description                                         |
| --------------------- | -------------------------- | --------------------------------------------------- |
| **Ctrl + Shift + P**, **F1**  | Show Command Palette        | Open quick actions and commands                     |
| **Ctrl + P**                  | Quick Open (Go to File)      | Quickly open files in the workspace                |
| **Ctrl + Shift + N**          | New Window / Instance        | Open a new instance of VS Code                      |
| **Ctrl + Shift + W**          | Close Window / Instance      | Close the current VS Code window                    |
| **Ctrl + K**, **Ctrl + S**    | Open Keyboard Shortcuts      | View and customize keyboard shortcuts               |

---

## 2) Basic Editing
| Shortcut                  | Command/Action             | Description                                                 |
| ------------------------- | --------------------------- | ----------------------------------------------------------- |
| **Ctrl + X**             | Cut line (no selection)     | Cuts the entire line if nothing is selected                |
| **Ctrl + C**             | Copy line (no selection)    | Copies the entire line if nothing is selected              |
| **Alt + ↑ / ↓**          | Move line up/down           | Moves the current line or selection up/down                |
| **Shift + Alt + ↑ / ↓**  | Copy line up/down           | Copies the current line or selection up/down               |
| **Ctrl + Shift + K**     | Delete line                 | Deletes the entire current line                            |
| **Ctrl + Enter**         | Insert line below           | Inserts a new line below the current line                  |
| **Ctrl + Shift + Enter** | Insert line above           | Inserts a new line above the current line                  |
| **Ctrl + ] / Ctrl + [**  | Indent / Outdent line       | Shifts text right/left                                     |
| **Ctrl + Home / Ctrl + End** | Go to file start / file end | Moves cursor to the beginning/end of the file          |
| **Home / End**           | Go to line start / line end | Moves cursor to the beginning/end of the line              |
| **Ctrl + ↑ / ↓**         | Scroll line up/down         | Scrolls the editor without moving cursor                   |
| **Ctrl + PgUp / PgDn**   | Scroll page up/down         | Scrolls by page in the editor                              |
| **Ctrl + Shift + [**     | Fold (collapse) region      | Collapses the current code region                          |
| **Ctrl + Shift + ]**     | Unfold (expand) region      | Expands the current code region                            |
| **Ctrl + K**, **Ctrl + [** | Fold all subregions          | Collapses all nested regions in the file               |
| **Ctrl + K**, **Ctrl + ]** | Unfold all subregions        | Expands all nested regions in the file                 |
| **Ctrl + K**, **Ctrl + 0** | Fold all                    | Collapses all code regions                                |
| **Ctrl + K**, **Ctrl + J** | Unfold all                  | Expands all code regions                                  |
| **Ctrl + /**             | Toggle line comment          | Comments/uncomments the current line/selection            |
| **Ctrl + K**, **Ctrl + C** | Add line comment             | Adds line comment for the current line/selection      |
| **Ctrl + K**, **Ctrl + U** | Remove line comment          | Removes comment for the current line/selection        |
| **Alt + Z**              | Toggle word wrap             | Wraps text to fit the editor width                        |

---

## 3) Navigation
| Shortcut            | Command/Action                   | Description                                              |
| ------------------- | -------------------------------- | -------------------------------------------------------- |
| **Ctrl + T**        | Show all symbols                 | Lists all symbols in the workspace                       |
| **Ctrl + G**        | Go to line…                      | Jump to specific line number                             |
| **Ctrl + P**        | Go to file… (Quick Open)         | Quickly open files in the workspace                     |
| **Ctrl + Shift + O**| Go to symbol in file…            | Jump to symbols in the current file                      |
| **Ctrl + Shift + M**| Show Problems panel              | Opens the “Problems” view (errors, warnings)            |
| **F8 / Shift + F8** | Next / previous error or warning | Jumps to the next/previous error or warning             |
| **Ctrl + Shift + Tab** | Navigate editor group history | Cycles through previously opened editors in a group      |
| **Alt + ← / Alt + →**| Go back / forward               | Moves backward/forward in the navigation history        |

---

## 4) Search and Replace
| Shortcut           | Command/Action                    | Description                                                   |
| ------------------ | --------------------------------- | ------------------------------------------------------------- |
| **Ctrl + F**       | Find                              | Searches text in the current file                             |
| **Ctrl + H**       | Replace                           | Replaces text in the current file                             |
| **F3 / Shift + F3**| Find next / previous              | Moves to the next/previous match                              |
| **Alt + Enter**    | Select all occurrences of match   | Highlights all current search matches                         |
| **Ctrl + D**       | Add selection to next find match  | Repeats selection for the next found text                     |
| **Ctrl + K**, **Ctrl + D** | Move last selection to next find match | Skips the current match and selects the next      |
| **Alt + C / R / W**| Toggle case-sensitive / regex / whole word | Modifies find options                               |

---

## 5) Multi-Cursor & Selection
| Shortcut                         | Command/Action                             | Description                                                 |
| -------------------------------- | ------------------------------------------ | ----------------------------------------------------------- |
| **Alt + Click**                 | Insert cursor at clicked location          | Adds a new cursor where you click                           |
| **Ctrl + Alt + ↑ / ↓**          | Insert cursor above / below                | Adds additional cursors above/below the current line        |
| **Ctrl + U**                    | Undo last cursor operation                 | Removes the most recent multi-cursor                        |
| **Shift + Alt + I**             | Insert cursor at end of each selected line | Places a cursor at the end of every selected line           |
| **Ctrl + I**                    | Select current line                        | Highlights the entire current line                          |
| **Ctrl + Shift + L**            | Select all occurrences of selection        | Highlights all matches of the current selection             |
| **Ctrl + F2**                   | Select all occurrences of current word     | Highlights all instances of the word under cursor           |
| **Shift + Alt + → / ←**         | Expand / shrink selection                  | Adjusts the selection by one word/character at a time       |
| **Ctrl + Shift + Alt + ↑ / ↓**  | Column (box) selection                     | Creates a rectangular selection with multiple cursors       |

---

## 6) File Management
| Shortcut                           | Command/Action             | Description                                               |
| ---------------------------------- | --------------------------- | --------------------------------------------------------- |
| **Ctrl + N**                       | New file                   | Creates a new file in VS Code                             |
| **Ctrl + O**                       | Open file…                 | Opens a file browser prompt                               |
| **Ctrl + S**                       | Save file                  | Saves the current file                                    |
| **Ctrl + Shift + S**               | Save As…                   | Saves the file under a new name                           |
| **Ctrl + K**, **S**                | Save all                   | Saves all open files                                      |
| **Ctrl + W** or **Ctrl + F4**      | Close editor               | Closes the current file/tab                               |
| **Ctrl + K**, **Ctrl + W**         | Close all editors          | Closes all open files/tabs in the current window          |
| **Ctrl + Shift + T**               | Reopen closed editor       | Reopens the last closed editor/tab                        |
| **Ctrl + K**, **Enter**            | Keep preview mode editor open | Pins the current preview editor                        |
| **Ctrl + Tab / Ctrl + Shift + Tab**| Next / previous open file  | Cycles through open tabs in the editor group              |
| **Ctrl + K**, **R**                | Reveal active file in Explorer | Highlights the current file in the Explorer panel     |
| **Ctrl + K**, **O**                | Open file in new window    | Opens the active file in a new VS Code window             |

---

## 7) Display
| Shortcut             | Command/Action                             | Description                                            |
| -------------------- | ------------------------------------------ | ------------------------------------------------------ |
| **F11**             | Toggle full screen                          | Enters or exits full-screen mode                      |
| **Shift + Alt + 0** | Toggle editor layout (horizontal/vertical)  | Splits the editor layout horizontally or vertically   |
| **Ctrl + = / Ctrl -** | Zoom in / zoom out                          | Changes the editor zoom level                         |
| **Ctrl + B**         | Toggle sidebar visibility                   | Shows/hides the sidebar                               |
| **Ctrl + Shift + E** | Show Explorer / Toggle focus                | Opens the Explorer or toggles focus to it             |
| **Ctrl + Shift + G** | Show Source Control                         | Opens the Git/Source Control view                     |
| **Ctrl + Shift + D** | Show Debug                                  | Opens the Debug view                                  |
| **Ctrl + Shift + X** | Show Extensions                             | Opens the Extensions panel                            |
| **Ctrl + Shift + H** | Replace in files                            | Opens the global find/replace panel                   |
| **Ctrl + Shift + J** | Toggle search details                       | Expands advanced search options                       |
| **Ctrl + Shift + U** | Show Output panel                           | Displays the Output panel                             |
| **Ctrl + Shift + V** | Open Markdown preview                       | Shows MD preview in the current editor               |
| **Ctrl + K**, **V**  | Open Markdown preview to the side          | Splits editor and shows MD preview in new pane        |
| **Ctrl + K**, **Z**  | Zen mode                                   | Enters minimal UI mode (press *Esc* twice to exit)    |

---

## 8) Debug
| Shortcut         | Command/Action          | Description                                       |
| ---------------- | ----------------------- | ------------------------------------------------- |
| **F9**           | Toggle breakpoint       | Adds or removes a breakpoint on the current line |
| **F5**           | Start/Continue debugging | Begins or resumes the debug session              |
| **Shift + F5**   | Stop debugging          | Ends the current debug session                   |
| **F11 / Shift + F11** | Step into / Step out   | Steps into/steps out of a function call          |
| **F10**          | Step over              | Runs the next statement, skipping function calls |
| **Ctrl + K**, **Ctrl + I** | Show hover (information) | Displays type info/quick info at mouse location  |

---

## 9) Integrated Terminal
| Shortcut                | Command/Action                 | Description                                       |
| ----------------------- | ------------------------------ | ------------------------------------------------- |
| **Ctrl + \`** (backtick)| Show/hide integrated terminal  | Toggles the built-in terminal panel              |
| **Ctrl + Shift + \`**   | Create new terminal            | Opens another terminal session                   |
| **Ctrl + C**            | Copy selection (in terminal)   | Copies highlighted text in the terminal          |
| **Ctrl + V**            | Paste into terminal            | Pastes clipboard content into terminal           |
| **Ctrl + Alt + ↑ / ↓**  | Scroll terminal up/down        | Scrolls the terminal view                        |
| **Ctrl + Home / End**   | Scroll to top/bottom of terminal | Jumps to the start/end of terminal buffer     |

---

## 10) Editor Management
| Shortcut                       | Command/Action                      | Description                                       |
| ----------------------------- | ----------------------------------- | ------------------------------------------------- |
| **Ctrl + F4**, **Ctrl + W**   | Close editor                        | Closes the active file/tab                        |
| **Ctrl + \\**                 | Split editor                        | Splits the current editor into two panes          |
| **Ctrl + 1 / 2 / 3**          | Focus into 1st / 2nd / 3rd editor   | Moves focus to a specific editor group            |
| **Ctrl + Shift + PgUp / PgDn**| Move active editor left / right     | Rearranges tabs within the editor group           |
| **Ctrl + K**, **Ctrl + W**    | Close all editors                   | Closes all open files/tabs in the current group   |

---

## 11) Rich Languages Editing
| Shortcut                 | Command/Action                      | Description                                               |
| ------------------------ | ----------------------------------- | --------------------------------------------------------- |
| **Ctrl + Space**         | Trigger suggestion                  | Opens IntelliSense suggestions                            |
| **Ctrl + Shift + Space** | Trigger parameter hints             | Shows parameter info for calls                            |
| **Tab**                  | Emmet expand abbreviation           | Expands Emmet/HTML abbreviations (in HTML/JSX, etc.)      |
| **Shift + Alt + F**      | Format document                     | Auto-formats the entire file                              |
| **Ctrl + K**, **Ctrl + F** | Format selection                    | Formats only the selected text                            |
| **F12**                  | Go to definition                    | Navigates to symbol definition                            |
| **Alt + F12**            | Peek definition                     | Opens a small inline peek window                          |
| **Ctrl + K**, **F12**    | Open definition to the side         | Splits and shows definition on the side                   |
| **Ctrl + .**             | Quick fix (code actions)            | Suggests fixes/refactoring                                |
| **Shift + F12**          | Show references                     | Lists all references of the symbol                        |
| **F2**                   | Rename symbol                       | Renames all occurrences of the symbol                     |
| **Ctrl + K**, **Ctrl + X** | Trim trailing whitespace           | Removes extra spaces at line endings                      |
| **Ctrl + K**, **M**      | Change file language                | Select a different language mode                          |
