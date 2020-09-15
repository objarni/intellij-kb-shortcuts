PyCharm keyboard shortcuts
==========================

Since I'm using PyCharm quite a lot these days, and I've noticed some issues with PyCharms sync-settings functionality, I want to document the shortcuts I've added or just use a lot so I can re-create them when syncing bugs out.

I base my shortcuts on the 'Sublime Text' keymap.


Favorites - general
-------------------
 * Shift, Shift = Search everything; both settings, content of project files and probably more I don't even know about! Really handy when unsure of what kb shortcut is used for something (also displays kb shortcut to the right of each option so learning builtin here)
 * Ctrl + D = Select next occurance. This is similar to Sublime Text's Ctrl + D
 * Alt + F3 = Select all occurances. Possibly more Python-aware than ST's Alt + F3
 * Ctrl + W = Close current window
 * Ctrl + L = Increase selection by surrounding cursor or previous selection in closest natural 'delimiter scope'
 * Ctrl + Alt + S = Settings. Especially useful when fiddling with .venv and such
 * Ctrl + PgUp/PgDown = Switch to left/right editor tab.
 * Alt + 1 = Focus project window (bring it up if it's closed)
 * Alt + 4 = Focus Run Window (handy with programs using input(..))
 * Alt + 2,2 = Bring up and hide Favorites window, basically giving focus to editor window. To get back from project or run window quickly!
 
 
Favorites - edit and refactor
-----------------------------
 * Ctrl + Alt + Shift + L, Enter = Reformat file (or selection if present)
 * Ctrl + Alt + Shift + T = Refactor this (bring up refactoring menu)
 * Ctrl + Shift + D = Duplicate current row.
 * Ctrl + Shift + Up/Down = Move line (or selection) up/down.
 * Ctrl + J = Snippet menu. Basically using this for `if __name__ == '__main__':` only :)


Custom shortcuts
----------------
Some things are just missing shortcuts for my workflow, so I've come up with my own:
 * Ctrl + O = File -> Open (duh! This is the first editor/IDE/desktop software that has lacked open kb shortcut since I started using software in the 80's... very surprising!)
 * Ctrl + Alt + Shift + W = Close other editor windows (when browsing lots of code this is handy for focusing on one of them)
 * Ctrl + Shift + S = Run with coverage. Using this a lot when doing approval testing
 * Ctrl + K = Commit window
 * Ctrl + Shift K = Push window



