# Sublime Text OS X Service (Finder)

These two OS X Services allow opening Sublime Text easily through the Services menu of OS X Finder. "Sublime" opens the file or folder in the current window, "Sublime New" opens a new Sublime Text Window. 

## Requirements

Sublime Text must be installed into /Applications and must have the name "Sublime Text.app".

## Keyboard Shortcuts

Keyboard schortcuts can be easily added for both services via the keyboard shortcut settings menu in OS X settings.

## Installation

Just copy the both directories (in Finder they are treated as a package / file) into ~/Library/Services

`cp *.workflow /Library/Services`

![Shortcut Screenshot](https://raw.githubusercontent.com/mjdev/SublimeService/gh-pages/images/shortcuts.png)