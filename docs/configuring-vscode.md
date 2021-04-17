# Configuring VSCode Text editor

The following snippets is purely opinationed, If you don't like any other styles feel free to remove those.

- [UI Changes](#ui-changes)
- [User Settings](#user-settings)
- [User Keybinding - (Softwares)](#user-keybindings)
- [User Snippets - (Softwares)](#user-snippets)

## UI Changes

1. You can use <a href="https://www.monolisa.dev/" target="_blank">MonoLisa</a>, <a href="https://www.jetbrains.com/lp/mono/" target="_blank">Operator Mono</a> or <a href="https://github.com/tonsky/FiraCode/wiki/Installing" target="_blank">Fira code (Free)</a> fonts.
2. Download external color theme <a href="https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme" target="_blank">**Palenight Theme - (Olaolu Olawuyi)**</a> from VSCode extensions.

Install the font in respect to your operating system and set the font, color theme in `user/settings.json` (`ctrl + .`)

```json
// UI Changes
"workbench.colorTheme": "Palenight Theme",
"editor.fontFamily": "MonoLisa", // or "Fire code"
"editor.fontSize": 15,
"editor.lineHeight": 45,
"editor.suggestFontSize": 15,
"editor.suggestLineHeight": 28,
"terminal.integrated.fontSize": 15,
"terminal.integrated.lineHeight": 1.5,
```

## User settings

```json
{
  /**
   * Better Defaults
   **/
  "editor.copyWithSyntaxHighlighting": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.emptySelectionClipboard": false,
  "workbench.editor.enablePreview": false,
  "window.newWindowDimensions": "inherit",
  "editor.multiCursorModifier": "ctrlCmd",
  "files.trimTrailingWhitespace": true,
  "diffEditor.renderSideBySide": false,
  "editor.snippetSuggestions": "top",
  "editor.detectIndentation": false,
  "window.nativeFullScreen": false,
  "files.insertFinalNewline": true,
  "files.trimFinalNewlines": true,

  /**
   * Hide Everything
   */
  "workbench.activityBar.visible": false,
  "workbench.sideBar.location": "right",
  "workbench.statusBar.visible": false,
  "workbench.editor.showTabs": false,
  "editor.renderIndentGuides": false,
  "editor.minimap.enabled": false,
  "editor.lineNumbers": "off",

  /**
   * Silence The Noise
   */
  "breadcrumbs.enabled": false,
  "scm.diffDecorations": "none",
  "editor.hover.enabled": false,
  "editor.matchBrackets": "never",
  "workbench.tips.enabled": false,
  "editor.colorDecorators": false,
  "git.decorations.enabled": false,
  "workbench.startupEditor": "none",
  "editor.lightbulb.enabled": false,
  "editor.selectionHighlight": false,
  "editor.overviewRulerBorder": false,
  "editor.renderLineHighlight": "none",
  "editor.occurrencesHighlight": false,
  "problems.decorations.enabled": false,
  "editor.renderControlCharacters": false,
  "editor.hideCursorInOverviewRuler": true,
  "editor.gotoLocation.multipleReferences": "goto",
  "editor.gotoLocation.multipleDefinitions": "goto",
  "editor.gotoLocation.multipleDeclarations": "goto",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "editor.gotoLocation.multipleImplementations": "goto",
  "editor.gotoLocation.multipleTypeDefinitions": "goto",

  /**
   * Find
   **/
  "search.useIgnoreFiles": false,
  "search.exclude": {
    // Hide everything in /vendor, except the "laravel" and "livewire" folder.
    "**/vendor/{[^l],?[^ai]}*": true,
    // Hide everything in /public, except "index.php"
    "**/public/{[^i],?[^n]}*": true,
    "**/node_modules": true,
    "**/dist": true,
    "**/_ide_helper.php": true,
    "**/composer.lock": true,
    "**/package-lock.json": true,
    "storage": true,
    ".phpunit.result.cache": true
  },

  /**
   * Code
   **/
  // Include "-" in word selection.
  "editor.wordSeparators": "`~!@#%^&*()=+[{]}\\|;:'\",.<>/?",
  "emmet.includeLanguages": {
    "blade": "html",
    "vue-html": "html",
    "vue": "html"
  },
  "files.associations": {
    ".php_cs": "php",
    ".php_cs.dist": "php"
  },

  /**
   * PHP
   **/
  "php.suggest.basic": false,

  /**
   * PHP CS Fixer
   **/
  "[php]": {
    "editor.defaultFormatter": "junstyle.php-cs-fixer"
  },
  "php-cs-fixer.onsave": true,
  "php-cs-fixer.showOutput": false,
  "php-cs-fixer.autoFixByBracket": false,
  "php-cs-fixer.rules": "@PSR2",

  /**
   * Prettier
   **/
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "prettier.requireConfig": true,
  "prettier.useEditorConfig": false,

  /**
   * Window Settings
   **/
  // "window.nativeTabs": true,
  "window.titleBarStyle": "native",
  "customizeUI.titleBar": "inline",
  "customizeUI.stylesheet": {
    ".editor .title": "background: transparent !important;",
    ".editor .title .label-container": "visibility: hidden;",
    // Hide top-right buttons
    ".editor .title .actions-container .action-item a": "visibility: hidden;",
    // Show top-right "settings goto icon"
    ".editor .title .actions-container .action-item a[title=\"Open Settings (UI)\"]": "visibility: initial;",
    ".editor .title .actions-container .action-item a[title=\"Open Settings (JSON)\"]": "visibility: initial;",
    // Make it the "right-most" icon.
    ".editor .title .actions-container": "flex-direction: row-reverse;",
    // Only show the scrollbar on hover.
    ".editor .scrollbar .slider": "visibility: hidden",
    ".editor .scrollbar:hover .slider": "visibility: initial",
    // Change cursor color.
    ".monaco-editor .cursor": "background: linear-gradient(to bottom, #7f00ff, #e100ff) !important; color: #292D3E !important"
  }
}
```

## User Keybindings

```json
[
  /**
   * Panels
   **/
  {
    "key": "cmd+k cmd+e",
    "command": "workbench.view.explorer"
  },
  {
    "key": "cmd+k cmd+g",
    "command": "workbench.view.scm"
  },
  {
    "key": "cmd+k cmd+d",
    "command": "workbench.view.debug"
  },
  {
    "key": "cmd+k cmd+x",
    "command": "workbench.extensions.action.showInstalledExtensions"
  },
  {
    "key": "cmd+k cmd+b",
    "command": "workbench.action.toggleSidebarVisibility"
  },
  {
    "key": "cmd+e",
    "command": "workbench.action.focusActiveEditorGroup"
  },
  {
    "key": "cmd+t",
    "command": "workbench.action.terminal.toggleTerminal"
  },

  /**
   * Toggle Font Size
   **/
  {
    "key": "cmd+k cmd+k",
    "command": "toggle",
    "when": "editorTextFocus",
    "args": {
      "id": "fontSize",
      "value": [
        {
          "editor.fontSize": 15,
          "editor.lineHeight": 45
        },
        {
          "editor.fontSize": 12,
          "editor.lineHeight": 0
        }
      ]
    }
  },

  /**
   * Fold/Unfold
   **/
  {
    "key": "shift+cmd+[",
    "command": "editor.fold",
    "when": "editorFocus"
  },
  {
    "key": "shift+cmd+]",
    "command": "editor.unfold",
    "when": "editorFocus"
  },

  /**
   * Line Manipulation
   **/
  {
    "key": "cmd+l",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+j",
    "command": "editor.action.joinLines",
    "when": "editorTextFocus"
  },

  /**
   * File Explorer
   **/
  {
    "key": "cmd+d",
    "command": "duplicate.execute",
    "when": "explorerViewletVisible && filesExplorerFocus && !explorerResourceIsRoot && !inputFocus"
  },
  {
    "key": "cmd+n",
    "command": "explorer.newFile",
    "when": "explorerViewletVisible && filesExplorerFocus && !inputFocus"
  },
  {
    "key": "shift+cmd+n",
    "command": "explorer.newFolder",
    "when": "explorerViewletVisible && filesExplorerFocus && !inputFocus"
  },

  /**
   * Multi-Cursor
   **/
  {
    "key": "cmd+backspace",
    "command": "editor.action.moveSelectionToPreviousFindMatch",
    "when": "editorFocus && editorHasMultipleSelections"
  },
  {
    "key": "cmd+k cmd+d",
    "command": "editor.action.moveSelectionToNextFindMatch",
    "when": "editorFocus && editorHasMultipleSelections"
  },
  {
    "key": "cmd+right",
    "command": "editor.action.insertCursorAtEndOfEachLineSelected",
    "when": "editorFocus && editorHasSelection"
  },

  /**
   * Split Panels
   **/
  {
    "key": "ctrl+w",
    "command": "workbench.action.joinAllGroups",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+n",
    "command": "workbench.action.splitEditor",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+l",
    "command": "workbench.action.navigateRight",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+h",
    "command": "workbench.action.navigateLeft",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+=",
    "command": "workbench.action.increaseViewSize",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+-",
    "command": "workbench.action.decreaseViewSize",
    "when": "editorFocus"
  },

  /**
   * Terminal Split Panel
   **/
  {
    "key": "ctrl+n",
    "command": "workbench.action.terminal.split",
    "when": "terminalFocus"
  },
  {
    "key": "ctrl+l",
    "command": "workbench.action.terminal.focusNextPane",
    "when": "terminalFocus"
  },
  {
    "key": "ctrl+h",
    "command": "workbench.action.terminal.focusPreviousPane",
    "when": "terminalFocus"
  },
  {
    "key": "ctrl+w",
    "command": "workbench.action.terminal.kill",
    "when": "terminalFocus"
  },

  /**
   * Emmet
   **/
  {
    "key": "cmd+m cmd+i",
    "command": "editor.emmet.action.balanceIn",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+o",
    "command": "editor.emmet.action.balanceOut",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+w",
    "command": "editor.emmet.action.wrapWithAbbreviation",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+m",
    "command": "editor.emmet.action.matchTag",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+e",
    "command": "editor.action.smartSelect.expand",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+r",
    "command": "editor.emmet.action.updateTag",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+m cmd+backspace",
    "command": "editor.emmet.action.removeTag",
    "when": "editorTextFocus"
  },

  /**
   * amVim Finder Fix
   **/
  {
    "key": "enter",
    "command": "editor.action.nextMatchFindAction",
    "when": "findWidgetVisible"
  },
  {
    "key": "shift+enter",
    "command": "editor.action.previousMatchFindAction",
    "when": "findWidgetVisible"
  },

  /**
   * IntelliSense
   **/
  {
    "key": "cmd+r",
    "command": "workbench.action.gotoSymbol"
  },
  {
    "key": "cmd+shift+r",
    "command": "workbench.action.showAllSymbols"
  },
  {
    "key": "cmd+k cmd+enter",
    "command": "editor.action.goToDeclaration",
    "when": "editorTextFocus"
  },
  {
    "key": "cmd+k cmd+i",
    "command": "namespaceResolver.import"
  },

  /**
   * Project Switching
   **/
  {
    "key": "cmd+;",
    "command": "workbench.action.switchWindow",
    "when": "! config.simple-project-switcher.present"
  },
  {
    "key": "alt+cmd+right",
    "command": "workbench.action.showNextWindowTab"
  },
  {
    "key": "alt+cmd+left",
    "command": "workbench.action.showPreviousWindowTab"
  },

  /**
   * Open DevTools
   **/
  {
    "key": "alt+cmd+i",
    "command": "workbench.action.toggleDevTools"
  },

  /**
   * Hide Toaster Notifications
   **/
  {
    "key": "escape",
    "command": "notifications.hideToasts",
    "when": "notificationToastsVisible"
  }
]
```

## User Snippets

This snippet page will be updated shortly!
