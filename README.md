# vscode-js

Visual Studio Code configuration files, settings and notes for editing JavaScript.

## Extensions

Extensions usefull for FTGP JavaScript development.

### Recommended extensions

Is also included in the workspace settings as the recommended extension.

| vscode extension name          | Marketplace name         |
| ------------------------------ | ------------------------ |
| `dbaeumer.vscode-eslint`       | ESLint                   |
| `dbaeumer.jshint`              | jshint                   |
| `msjsdiag.debugger-for-chrome` | Debugger for Chrome      |
| `lici.require-js`              | Require Module Support   |
| `eg2.vscode-npm-script`        | npm                      |
| `EditorConfig.EditorConfig`    | EditorConfig for VS Code |

### Nice to have extensions

| vscode extension name                   | Marketplace name                  |
| --------------------------------------- | --------------------------------- |
| `streetsidesoftware.code-spell-checker` | Code Spell Checker                |
| `Atishay-Jain.all-autocomplete`         | All Autocomplete                  |
| `naumovs.node-modules-resolve`          | Node modules resolve              |
| `leizongmin.node-module-intellisense`   | Node.js Modules Intellisense      |
| `christian-kohler.npm-intellisense`     | npm intellisense                  |
| `qrti.funclist`                         | Show functions                    |
| `lkytal.quicktask`                      | QuickTask (for running gulp, etc) |

## Settings

### Show functions extension

```json
"funcList.displayFilter": "/.*/",
"funcList.doubleSpacing": false,
"funcList.nativeFilter": "/(?:^|\\s)(?:my\\.|that\\.|var\\s+|let\\s+)\\w+(?:\\s*=\\s*\\S*|;\\S*)/mgi",
```

## Notes

WIP - More to come...