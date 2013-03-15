# Notepad++ SQF Syntax Highlighting and Auto Completion

Notepad++ syntax highlighting and autocompletion for SQF (the scripting language for the ArmA games).
All known functions from ArmA 3 (and previous titles) are supported. Code block folding is also supported.

## Installation


### Syntax Highlighting

Open Notepad++. Click in the menu on: "Language -> Define your own Language -> Import" and import the file "syntaxhighlighting/SQF.xml".

### Auto Completion

The steps in the section "Syntax Highlighting" are required for auto completion.
Copy the file "autocompletion/SQF.xml" into the folder "C:\Program Files (x86)\Notepad++\plugins\APIs" (or where you installed Notepad++).
Restart Notepad++. Open the settings in Notepad++. Go to the tab "Backup/Auto-Completion".

- Enable "Enable auto-completion on each input"
- Choose "Function completion"
- Set "From 3th character" (or what you prefer)

## How to modify styles

You can modify the styles via "Language -> Define your own Language". Select "SQF" (under "User language").