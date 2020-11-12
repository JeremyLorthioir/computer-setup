# Steps to setup a new computer

### Basic applications

- [Git Kraken](https://www.gitkraken.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Koala](http://koala-app.com/)

### VSC Setup

- **General setup**
    - [Cobalt2 Theme](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)
    - [Cascadia code font](https://github.com/microsoft/cascadia-code)
    - [Fira code symbols](https://github.com/tonsky/FiraCode)
  

- **Extensions**
    - [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
    - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
    - [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
    - [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    - [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

- **Configuration file**
  - Mac Os : `~/Library/Application Support/Code/User/settings.json`
  - Linux : `~/.config/Code/User/settings.json`
  - Windows : `%APPDATA%\Code\User\settings.json`
 
```json
{
    "workbench.colorTheme": "Cobalt2",
    "explorer.confirmDelete": false,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.formatOnSave": true,
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 60,
    "git.autofetch": true,
    "git.confirmSync": false,
    "explorer.confirmDragAndDrop": false,
    "prettier.useTabs": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "typescript.updateImportsOnFileMove.enabled": "always",
    "editor.fontFamily": "'fira code'",
    "editor.fontLigatures": true
}
```

### Apache, MySQL, PHP 
