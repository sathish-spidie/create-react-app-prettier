## Just Click use this template button

## OR

## Adding prettier without ejecting "react-script" With VScode.

## Extenstion Requirements

1. Es-lint
2. Prittier

## Also some wire up's needed 

Use this [code](https://gist.github.com/sathish-spidie/4a478594cacb333c0f4ff7c3b4fd38fd)

## OR

### Just clone This repo 

### Run `npm install`

### AND Paste this code in settings.json in your vscode.

```
{
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
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    { "language": "typescript", "autoFix": true },
    { "language": "typescriptreact", "autoFix": true }
  ]
}
```

### That's it you're Ready to go now But don't forget do Add Extenstions!








