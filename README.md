# Pathetic's Extension pack

> This contains my recommended plugins for C/C++, Python, Dart, Ruby, Go, JavaScript, Tailwind, Svelte, React Native, Docker, Solidity, Databases (MySQL, PostgreSQL etc)

## Customization:

### Themes Included:
- Bearded themes
- One dark pro
- Github themes

How to change your theme:

Press `CTRL + Shift + P` and search for `Preferences: Color theme` and and select the one you like

### Icons Included:
- Bearded icons
- VS Code icons
- Material icons

How to change your icons:

Press `CTRL + Shift + P` and search for `Preferences: File icon theme` and select the one you like

### Font:

I'd recommend you to install [Fira Code](https://github.com/tonsky/FiraCode). If you don't want it just edit `"editor.fontFamily"` property in `settings.json` below

## `settings.json` file

Press `CTRL + Shift + P` and search for `Preferences: Open settings (JSON)` and copy paste the following:

```json
{
  "workbench.colorTheme": "BeardedTheme Black & Emerald",
  "workbench.iconTheme": "bearded-icons",
  "workbench.startupEditor": "none",
  "editor.accessibilitySupport": "off",
  "editor.minimap.enabled": false,
  "editor.hover.delay": 900,
  "editor.tabSize": 2,
  "editor.fontSize": 13,
  "editor.fontLigatures": true,
  "editor.fontWeight": "500",
  "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
  "editor.wordWrapColumn": 140,
  "editor.defaultFormatter": "rvest.vs-code-prettier-eslint",
  "editor.cursorBlinking": "expand",
  "editor.renderControlCharacters": false,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.organizeImports": true,
    "source.fixAll": true
  },
  "html.format.indentInnerHtml": true,
  "explorer.confirmDragAndDrop": false,
  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "git.allowForcePush": true,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/node_modules": true
  },
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/**": true
  },
  "emmet.includeLanguages": {
    "vue-html": "html",
    "javascript": "javascriptreact"
  },
  "editor.quickSuggestions": {
    "strings": true
  },
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "dart.debugExternalLibraries": false,
  "dart.debugSdkLibraries": false,
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [80],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  "C_Cpp.updateChannel": "Insiders",
  "[c]": {
    "editor.tabSize": 4,
    "editor.defaultFormatter": "ms-vscode.cpptools"
  },
  "[cpp]": {
    "editor.tabSize": 4,
    "editor.defaultFormatter": "ms-vscode.cpptools"
  },
  "python.languageServer": "Pylance",
  "python.formatting.provider": "black",
  "python.formatting.blackArgs": [
    "--line-length=119"
  ],
  "python.sortImports.args": [
    "--profile=black"
  ],
  "[python]": {
    "gitlens.codeLens.symbolScopes": ["!Module"],
    "editor.defaultFormatter": "ms-python.python",
  },
  "[go]": {
    "editor.defaultFormatter": "golang.go"
  },
  "solargraph.formatting": true,
  "[ruby]": {
    "editor.defaultFormatter": "castwide.solargraph",
  },
  "solidity.compileUsingRemoteVersion": "soljson-v0.5.17+commit.d19bba13",
  "python.showStartPage": false,
  "docker.showStartPage": false,
  "vsicons.dontShowNewVersionMessage": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "editor.linkedEditing": true,
}
```