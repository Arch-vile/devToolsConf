# VS CODE

## Linting

### Eslint

For some reason the Eslint plugin did not flag errors off the box so needed to set the config:
```
  // Eslint plugin enable (https://marketplace.visualstudio.com/items/?itemName=dbaeumer.vscode-eslint)
  "eslint.enable": true,
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],

```
