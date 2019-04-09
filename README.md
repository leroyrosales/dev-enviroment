# Xcode
-----
- You have two options for installing xcode.  The full package or just the
command line tools but at a minimum the command line tools are required.
- Install just the xcode command line tools with:
- `xcode-select --install` -or-
- Go to the app store and download the full package.  The full package is
great for if you do any sort of mobile development.

# Manual Download Applications
----------------------------
- Google Chrome (https://www.google.com/intl/en/chrome/browser/)
- Firefox (https://www.mozilla.org/en-US/firefox/new/)
- Slack (App store)

# Pre Install Configuration
-------------------------
- Setup SSH Key
- Setup SSH Key on GitHub
- Setup SSH Key on Digital Ocean

# iTerm2
------
- Download iTerm2 (https://iterm2.com/downloads/stable/iTerm2-2_1_4.zip)
- Move the unarchived app to your Applications/Utilities directory
- Open the app
- Open preferences
- Uncheck confirm "closing multiple sessions"
- Uncheck confirm "Quit iTerm2 (Cmd+Q)"
- Change fonts to Consolas 14pt font

# Nano
----
- Take 5 minutes to learn the nano text editor and save yourself the hassle of
learning vim

# VIM
---
- Learn how to get out of vim use the following:
- `:q`

# Visual Studio Code
[https://code.visualstudio.com/](https://code.visualstudio.com/)

Set up shell command: [https://code.visualstudio.com/docs/setup/mac](https://code.visualstudio.com/docs/setup/mac)

# VS Code Extensions
* Bracket Pair Colorizer
* indent-rainbow
* Live Sass Compiler
* Javascript ES6 code snippets
* Live Server
* Prettier - Code Formatter
* stylelint
* Twig
* VS Color Picker
* vscode-icons

# VS Code Settings
-------------
The settings are configured via 'Settings' and are maintained via JSON.
To override, just click on the pencil icon next to the code-to-be-overwritten and select 'Replace in settings'. This adds a line to the custom settings JSON on the right.

**Example**
```
{
    "workbench.startupEditor": "newUntitledFile",
    "liveServer.settings.donotShowInfoMsg": true,
    "workbench.colorTheme": "Visual Studio Dark",
    "emmet.triggerExpansionOnTab": true,
    "vsicons.dontShowNewVersionMessage": true,
    "explorer.confirmDragAndDrop": false,
    "editor.fontSize": 14
}
```

# Lando Installation
[https://docs.devwithlando.io/installation/macos.html](https://docs.devwithlando.io/installation/macos.html)

# NVM
----
- `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash`
- `npm install gulp -g`
- `npm install grunt -g`