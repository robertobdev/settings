# Settings
My personal settings

# Vscode settings json
```
{ 
  //Personal 
  "editor.fontSize": 17.5,
  "editor.lineHeight": 20,
  "editor.fontFamily": "Fira Code",
  "editor.minimap.enabled": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.formatOnType": true,
  "editor.formatOnPaste": true,
  "editor.mouseWheelZoom": false,
  "editor.renderLineHighlight": "gutter",
  "window.zoomLevel": 0,
  "editor.quickSuggestions": {
      "other": true,
      "comments": true,
      "strings": true
  },
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Allure Contrast (rainglow)", // "Visual Studio Light",
  "git.confirmSync": false,
  "editor.codeLens": true,
  "search.exclude": {
      "**/.git": true,
      "**/node_modules": true,
      "**/bower_components": true,
      "**/tmp": true,
      "**/www": true
  },
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "terminal.integrated.fontSize": 14,
  "files.autoSave": "off",
  "breadcrumbs.enabled": true,
  "editor.renderIndentGuides": false,
  "[typescript]": {
      "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[html]": {
      "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[css]": {
      "editor.defaultFormatter": "aeschli.vscode-css-formatter"
  },
  "git.autofetch": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "[javascript]": {
      "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  //Standard
  "editor.codeActionsOnSave": {
      "source.fixAll.tslint": true
  }
}
```

# Vscode extensions
```
#Standard

code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension dbaeumer.vscode-eslint
code --install-extension EditorConfig.EditorConfig
code --install-extension Angular.ng-template
code --install-extension aeschli.vscode-css-formatter
code --install-extension danwahlin.angular2-snippets
code --install-extension mikestead.dotenv
code --install-extension eamodio.gitlens
code --install-extension christian-kohler.path-intellisense
code --install-extension formulahendry.auto-close-tag
code --install-extension wayou.vscode-todo-highlight

#Personal
code --install-extension naumovs.color-highlight
code --install-extension ms-vscode.sublime-keybindings
code --install-extension PKief.material-icon-theme
code --install-extension spywhere.guides
code --install-extension Zignd.html-css-class-completion
code --install-extension dracula-theme.theme-dracula
code --install-extension daylerees.rainglow
code --install-extension 2gua.rainbow-brackets

```
