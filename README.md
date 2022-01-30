# Settings
My personal settings

# Vscode settings json
```
{
  "editor.fontSize": 17,
  "editor.lineHeight": 20.5,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.minimap.enabled": false,
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.codeLens": true,
  "editor.renderLineHighlight": "gutter",
  "editor.formatOnType": true,
  "editor.formatOnPaste": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true
  },
  "workbench.iconTheme": "vscode-icons",
  "workbench.colorTheme": "One Dark Pro",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "search.exclude": {
    "**/.git": true,
    "**/node_modules": true,
    "**/tmp": true,
    "**/www": true,
    "**/dist": true
  },
  "files.autoSave": "off",
  "explorer.compactFolders": false,
  "git.autofetch": true,
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "XXX",
    "[ ]",
    "[x]"
  ],
  "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "editor.suggestSelection": "first",
  "files.exclude": {
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "terminal.integrated.profiles.osx": {
    "bash": {
      "path": "bash",
      "args": [
        "-l"
      ],
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh",
      "args": [
        "-l"
      ]
    },
    "fish": {
      "path": "fish",
      "args": [
        "-l"
      ]
    },
    "tmux": {
      "path": "tmux",
      "icon": "terminal-tmux"
    },
    "pwsh": {
      "path": "pwsh",
      "icon": "terminal-powershell"
    }
  },
  "terminal.integrated.defaultProfile.osx": "fish",
  "html.format.enable": false
}

```

# Vscode extensions
```
// Standard

code --install-extension Angular.ng-template
code --install-extension dbaeumer.vscode-eslint
code --install-extension eamodio.gitlens
code --install-extension EditorConfig.EditorConfig
code --install-extension Gruntfuggly.todo-tree
code --install-extension mikestead.dotenv
code --install-extension ms-vscode.sublime-keybindings
code --install-extension PKief.material-icon-theme
code --install-extension stylelint.vscode-stylelint
code --install-extension zhuangtongfa.material-theme

// Optional
code --install-extension esbenp.prettier-vscode

```
