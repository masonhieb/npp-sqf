# Notepad++ SQF Syntax Highlighting and Auto Completion

Notepad++ syntax highlighting and autocompletion for SQF (the scripting language for the ArmA games).  
All known functions from ArmA 3 (and previous titles) are supported. Code block folding is also supported.

## Installation


### Syntax Highlighting

1. Open Notepad++.
2. Click in the menu on: "Language -> Define your own Language -> Import".
3. Import the file "syntaxhighlighting/SQF.xml".
4. Restart Notepad++.

### Auto Completion

The steps in the section "Syntax Highlighting" are required for auto completion.

1. Copy the file "autocompletion/SQF.xml" into the folder "C:\Program Files (x86)\Notepad++\plugins\APIs" (or where you installed Notepad++).
2. Restart Notepad++.
3. Open "Settings -> Preferences..." in Notepad++.
4. Go to the tab "Backup/Auto-Completion".
5. Choose following options:
  - Enable "Enable auto-completion on each input"
  - Choose "Function completion"
  - Set "From 3th character" (or what you prefer)

## How to modify styles

You can modify the styles via "Language -> Define your own Language". Select "SQF" (under "User language").
