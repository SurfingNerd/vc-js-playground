# nodejs-ts

A template for node.js projects set up to use TypeScript

To run src/index.ts and watch for changes:
```
npm i
npm run dev
```

## Visual Studio Code

Install the "tslint" extension:
https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin

Activate tslint auto-fix on save:
Open your Visual Studio User Settings file (Linux: `code $HOME/.config/Code/User/settings.json
`) and add the following inside the curly braces of that json file:
```
    "editor.codeActionsOnSave": {
        "source.fixAll.tslint": true,
    }
```
