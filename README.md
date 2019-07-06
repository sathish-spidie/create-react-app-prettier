## Adding prettier without ejecting "react-script" With VScode.

## Extenstion Requirements

1. Es-lint
2. Prittier

## Also some wire up's needed 

Use this [code](https://gist.github.com/sathish-spidie/999118ba64e0b4e5ba36bd35630264c0)

## OR

### Just clone This repo 

### Run `npm install`

### AND Paste this code in settings.json in your vscode.

```{
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "prettier.disableLanguages": [
    "js"
  ],
  "files.autoSave": "onFocusChange",
  // It fixes some wired {" "} stufs in code.
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    { "language": "typescript", "autoFix": true },
    { "language": "typescriptreact", "autoFix": true }
  ]
}```








