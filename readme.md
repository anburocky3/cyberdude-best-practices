# Development Best Practices

These documentation is to ensure smooth, productive environment to develop apps faster. Please follow all the recommendations strictly to avoid confusion with the team.


## License
MIT (**Fork with care**), Created by [Anbuselvan Rocky](https://github.com/anburocky3)

## Tools needed

We use the following open source tools in our projects.

1. [Install Editor - How to install VSCode text editor?](#installing-vscode-text-editor)
2. [Install Extensions - Increase Productivity!](#installing-vscode-extensions)
3. [Configure - Making VSCode smart!](#configuring-vscode-text-editor)

<hr style="margin: 40px 0">

# Installing VSCode Text Editor

Learn how to install <a href="https://code.visualstudio.com" target="_blank">VSCode Text Editor</a> from this documentation.

---

## Downloading the app

1. Download the <a href="https://code.visualstudio.com/download" target="_blank">setup</a> based on your Operation system.
2. Follow the installation according to your operating system. For [Windows](#for-windows), [Linux](#for-ubuntu) based operating systems.

### For Windows

Run the download setup file and follow the onscreen installation. It is so simple as that.

1. Run the setup file, accept the license agreement and click `Next` button.

   ![VSCode Setup Dialog](/images/installing-vscode/1.png)

2. Check all Checkbox and click `Next`.

   ![VSCode Setup Dialog](/images/installing-vscode/2.png)

   > Don't forgot to check the all occurance of `Open with Code` & `Add to PATH`.

3. Click `Install` to install it in your system.

   ![VSCode Setup Dialog](/images/installing-vscode/3.png)

4. Click `Finish`. You can successfully installed the vscode text editor.

   ![VSCode Setup Dialog](/images/installing-vscode/4.png)

### For Ubuntu

You can download the vscode application directly via `terminal` through [snap packages](https://snapcraft.io/code).
Just use the following command to install vscode in Linux based Operating systems.

```zsh
sudo snap install code --classic
```

Once, you have successfully installed, you can [start installing the required extensions](#installing-vscode-extensions).

<hr style="margin: 40px 0">

# Installing VSCode Extensions

Download the useful extensions based on your project. Choose your project platform and choose the extensions accordingly.

- [Frontend Projects](#frontend-projects) ([React](#react-projects), [Vue](#vue-projects), Angular, [Tailwind CSS](#tailwindcss-projects), [Bootstrap](#bootstrap-projects) & even simple web UI)
- [PHP Projects - (Softwares)](#php-projects)
- [Python Projects - (Softwares)](#python-projects)
- [Android, Flutter Projects - (Softwares)](#android-projects)
- [Indic language typing software](#indic-language-typing-software)

## Frontend projects

if you are building apps using any one of the frontend technologies like (React, Vue, Angular, and probably other js frameworks too). We suggest the following extensions

1. <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer" target="_blank">Live Server (Ritwick Dey)</a> - Launch a local development server with live reload feature for static & dynamic pages.
2. <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode" target="_blank">Prettier - Code Formatter</a> - Prettier is an opinionated code formatter.
3. <a href="https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify" target="_blank">Beautify - HookyQR</a> - For HTML, PHP (blade) and so on.
4. Install <a href="https://nodejs.org/en/download/" target="_blank">Node.js, npm</a> or <a href="https://classic.yarnpkg.com/en/docs/install/yarn" target="_blank"> Yarn</a> for Javascript based projects
5. (Don't forget to check Emmet tricks too)

### React projects

1.  <a href="https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets" target="_blank">Simple React Snippets - (Burke Holland)</a> - The essential collection of React Snippets and commands.

### Vue projects

1.  <a href="https://marketplace.visualstudio.com/items?itemName=octref.vetur" target="_blank">Vetur - (Pine Wu)</a> - Vue tooling for VS Code.

### TailwindCSS projects

1.  <a href="https://marketplace.visualstudio.com/items?itemName=octref.vetur" target="_blank">Tailwind CSS IntelliSense - (Brad Cornes)</a> - Tailwind CSS IntelliSense enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

### Bootstrap projects

1.  <a href="https://marketplace.visualstudio.com/items?itemName=octref.vetur" target="_blank">Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets - (Ashok Koyi)</a> - Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets for Visual studio code

### VSCode UI Experiences

1.  <a href="https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons" target="_blank">vscode-icons</a> - Bring icons to your Visual Studio Code.

<hr style="margin: 20px 0">

## PHP Projects

if you are building web apps using PHP, then we suggest the following addons.

1. <a href="https://laragon.org/download/" target="_blank">Laragon - Portable Web Server</a> - Laragon is a universal development environment.
2. <a href="https://www.jetbrains.com/phpstorm/download/" target="_blank">PHPStorm - IDE (Paid)</a> <small>(Optional)</small> - PHP IDE for rapid development.
3. <a href="https://dev.mysql.com/downloads/workbench/" target="_blank">MySQL Workbench - Database Tool</a> <small>(Optional)</small> - For rapid database operations.
4. [Includes all frontend tools](#frontend-projects) - Since we are going to work with frontend, we have install those.
5. Install <a href="https://getcomposer.org/download/" target="_blank">Composer</a> <small>(Optional if Laragon installed)</small> - Package managers for PHP.
6. PHP Extensions
   1. <a href="https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client" target="_blank">PHP Intelephense - (Ben Mewburn)</a> - PHP code intelligence for Visual Studio Code.

<hr style="margin: 20px 0">

## Python Projects

if you are using Python, then we suggest the following addons.

1. <a href="https://www.python.org/downloads/" target="_blank">Python Setup</a> - Includes the python executables.
2. <a href="https://www.jetbrains.com/pycharm/download/" target="_blank">PyCharm - IDE (Paid)</a> <small>(Optional)</small> - Python IDE for rapid development.
3. <a href="https://dev.mysql.com/downloads/workbench/" target="_blank">MySQL Workbench - Database Tool</a> <small>(Optional)</small> - For rapid database operations.
4. [Includes all frontend tools](#frontend-projects) - Since we are going to work with frontend, we have install those.
5. Install <a href="https://pip.pypa.io/en/stable/installing/" target="_blank">pip</a> <small>(Optional)</small> - Package managers for Python.
6. Python Extensions
   1. <a href="https://marketplace.visualstudio.com/items?itemName=ms-python.python" target="_blank">Python - (Microsoft)</a> - Python extension for Visual Studio Code

<hr style="margin: 20px 0">

## Android Projects

if you are developing apps using Kotlin, JAVA using Android Studio, then we suggest the following addons.

1. <a href="https://developer.android.com/studio" target="_blank">Android Studio Setup</a> - Includes the SDK, Emulators for developing android applications.

<hr style="margin: 20px 0">

## Indic language typing software

if you are using any indic languages like Tamil, Telugu, Malayalam, Hindi, Bengali, etc. then we suggest the following addons.

1. <a href="https://www.azhagi.com/" target="_blank">Azhagi Plus Setup</a> - Indic language typing software.

<hr style="margin: 40px 0">

# Configuring VSCode Text editor

The following snippets is purely opinationed, If you don't like any other styles feel free to remove those.

- [UI Changes](#ui-changes)
- [User Settings](#user-settings)
- [User Keybinding - (Softwares)](#user-keybindings)
- [User Snippets - (Softwares)](#user-snippets)

## UI Changes

1. You can use <a href="https://www.monolisa.dev/" target="_blank">MonoLisa</a>, <a href="https://www.jetbrains.com/lp/mono/" target="_blank">Operator Mono</a> or <a href="https://github.com/tonsky/FiraCode/wiki/Installing" target="_blank">Fira code (Free)</a> fonts. Alternatively, you can download [fonts here](/assets/fonts/fonts.zip)
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

```jsonc
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

   "beautify.language": {
    "html": ["html", "php", "erb"],
    "css": [],
    "js": []
  }
}
```

## User Keybindings

```jsonc
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
