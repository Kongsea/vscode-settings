# VSCode settings

## Extensions

- [Python by Microsoft](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [vscode-fileheader](https://marketplace.visualstudio.com/items?itemName=mikey.vscode-fileheader): Ctrl + Alt + I to insert a header.
- [Nomo Dark Icon Theme](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-icontheme-nomo-dark)

## [settings.json](./settings.json)
My user settings of VSCode

1. Fonts: name and size.

   "editor.fontLigatures": true is used to render fonts freely.

2. Render the indent lines.

   "editor.renderIndentGuides": true

3. Render whitespace of beginning of lines.

   "editor.renderWhitespace": "boundary"

4. Render editor color.

   "workbench.colorCustomizations"

5. Set settings for autopep8.

   "python.formatting.autopep8Args"

   set tab size combined with editor.tabSize.

6. Set settings for pylint.

   "python.formatting.autopep8Args"

7. Ignore some files and set them invisible.

   "files.exclude"

8. Save and format automatically.

   files.autoSave

   editor.formatOnSave

9. Set theme.

   workbench.iconTheme

   workbench.colorTheme

10. Set minimap.

    "editor.minimap.enabled"

    "editor.minimap.maxColumn"

## [python.json](./python.json)
My user snippets for Python using Python extension by Don Jayamanne.

File path: ~/.vscode/extensions/ms-python.python-***/snippets/python.json

1. pc

   Python path and coding format.

2. pc3

   Python 3 path and coding format.

3. ds

   Document string and author information.

4. ff

   `from __future__ import ...`

5. inmp or inm

   `import numpy as np`

6. icp

   `import cPickle as pickle`

7. impp

   `import matplotlib.pyplot as plt`

8. itf

   `import tensorflow as tf`

9. ifm

   Create a main function structure.

## [keybindings.json](./keybindings.json)
My key bindings of VSCode.

File path: ~/.config/Code/User/keybindings.json

1. Back and forward

   Ctrl + F11 or Ctrl + F12

2. Toggle output

   F4

3. Delete current line

   Alt + Delete (not disturb the copyboard) or
   Ctrl + X (can cut current line with nothing selected but disturb the copyboard)

4. Cut current line

   Shift + Delete or Ctrl + X (can cut current line with nothing selected)

5. Copy current line

   Ctrl + C (can copy current line with nothing selected)

6. Move current line down

   Alt + Down

7. Move current line up

   Alt + Up

8. Copy current line down

   Shift + Alt + Down

9. Copy current line up

   Shift + Alt + Up

## Some errors
1. Formatter autopep8 is not installed.

   Although autopep8 has been installed, vscode will give this error sometimes.

   How to fix:

     Install autopep8 using the Ubuntu package (not using pip as VSCode tries to do):

     `sudo apt-get install python-autopep8`

## Usage tips
[Record some usage tips using vscode.](./usage_tips.md)
