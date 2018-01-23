# vscode-js

Visual Studio Code configuration files, settings and notes for editing JavaScript.

## Notes

NB that these settings is WIP and it will not give you 100% functionality in form of symbol navigation and such.
It is also more strict when it comes to formatting, so be careful when formatting the documents since it might change
code that is considered well-formatted.

### Debugging

Visual Studio Code seems to have problem to sync the settings with the Chrome Developer Tools window if it is open.
So keep it closed if you want to honor the settings from the `launch.json` file, such as the `skipFiles` settings.

## Extensions

Extensions usefull for FTGP JavaScript development.

### Recommended extensions

The recommended extensions are also included in the workspace settings.

| vscode extension name          | Marketplace name         |
| ------------------------------ | ------------------------ |
| `dbaeumer.vscode-eslint`       | ESLint                   |
| `msjsdiag.debugger-for-chrome` | Debugger for Chrome      |
| `lici.require-js`              | Require Module Support   |
| `eg2.vscode-npm-script`        | npm                      |
| `EditorConfig.EditorConfig`    | EditorConfig for VS Code |

### Nice to have extensions

Many of these extensions should probably be added to the list of recommended ones as well,
so do not hesitate to try them out since they will make your life easier for sure.

| vscode extension name                   | Marketplace name                  |
| --------------------------------------- | --------------------------------- |
| `streetsidesoftware.code-spell-checker` | Code Spell Checker                |
| `Atishay-Jain.all-autocomplete`         | All Autocomplete                  |
| `naumovs.node-modules-resolve`          | Node modules resolve              |
| `leizongmin.node-module-intellisense`   | Node.js Modules Intellisense      |
| `christian-kohler.npm-intellisense`     | npm intellisense                  |
| `qrti.funclist`                         | Show functions                    |
| `lkytal.quicktask`                      | QuickTask (for running gulp, etc) |
| `yzhang.markdown-all-in-one`            | Markdown All in One               |

## Settings

Useful settings that is not required, e.g. for the *Nice to have extensions* and such.

### Show functions extension

```json
"funcList.displayFilter": "/.*/",
"funcList.doubleSpacing": false,
"funcList.nativeFilter": "/(?:^|\\s)(?:my\\.|that\\.|var\\s+|let\\s+)\\w+(?:\\s*=\\s*\\S*|;\\S*)/mgi",
```