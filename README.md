*The below dev environment is set up for Mac.*

My Current OS: 
* macOS Mojave 10.14.4

My Current Hardware: 
* iMac Retina 5k Late 2015
* MB Air Retina 13-inch 2018


# Xcode
- You have two options for installing xcode.  The full package or just the
command line tools but at a minimum the command line tools are required.
- Install just the xcode command line tools with:
- `xcode-select --install` -or-
- Go to the app store and download the full package.  The full package is
great for if you do any sort of mobile development.

# Bash-it
- Git: [https://github.com/Bash-it/bash-it](https://github.com/Bash-it/bash-it)

# Yonce theme (for Bash-it, Slack, VS Code)
From the awesome Mina Markham!
[https://github.com/minamarkham/yonce](https://github.com/minamarkham/yonce)

# Manual Download Applications
- Google Chrome (https://www.google.com/intl/en/chrome/browser/)
- Firefox (https://www.mozilla.org/en-US/firefox/new/)
- Slack (App store)

# Pre Install Configuration
- Setup SSH Key
- Setup SSH Key on GitHub
- Setup SSH Key on Digital Ocean

# iTerm2
- Download iTerm2 (https://iterm2.com/downloads/stable/iTerm2-2_1_4.zip)
- Move the unarchived app to your Applications/Utilities directory
- Open the app
- Open preferences
- Uncheck confirm "closing multiple sessions"
- Uncheck confirm "Quit iTerm2 (Cmd+Q)"

# Nano
- Take 5 minutes to learn the nano text editor and save yourself the hassle of
learning vim

# VIM
- Learn how to get out of vim use the following:
- `:q`
- To close and save use:
- `:wq`

# Visual Studio Code
[https://code.visualstudio.com/](https://code.visualstudio.com/)

Set up shell command: [https://code.visualstudio.com/docs/setup/mac](https://code.visualstudio.com/docs/setup/mac)

# VS Code Extensions
* Bracket Pair Colorizer 2
* indent-rainbow
* Live Sass Compiler
* Javascript ES6 code snippets
* Live Server
* Prettier - Code Formatter
* stylelint
* Twig
* VS Color Picker
* vscode-icons
* auto rename tag
* rest client
* GitLens
* Auto-Open Markdown Preview
* Vetur (for when you use Vue more heavily)


# VS Code Settings
The settings are configured via 'Settings' and are maintained via JSON.
To override, just click on the pencil icon next to the code-to-be-overwritten and select 'Replace in settings'. This adds a line to the custom settings JSON on the right.

**Settings**
```
{
    "window.zoomLevel": 0,
    "explorer.confirmDragAndDrop": false,
    "python.pythonPath": "python3",
    "editor.fontSize": 14,
    "editor.tabSize": 4,
    "editor.wordWrap": "on",
    "terminal.integrated.fontSize": 16,
    "workbench.colorTheme": "Yoncé",
    "workbench.iconTheme": "vscode-icons",
    "vsicons.projectDetection.autoReload": true,
    "workbench.startupEditor": "newUntitledFile",
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.donotVerifyTags": true,
    "vsicons.dontShowNewVersionMessage": true,
    "liveSassCompile.settings.generateMap": false,
}
```

# Lando Installation
Spin up containers via the command line without having to mess with MAMP, Vagrant, and so forth. (Don't forget to install Docker beforehand!)

[https://docs.devwithlando.io/installation/macos.html](https://docs.devwithlando.io/installation/macos.html)

# Node Version Manager
- Repo: [https://github.com/creationix/nvm](https://github.com/creationix/nvm)
- `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash`
- `npm install gulp -g`
- `npm install grunt -g`

# Ruby Version Manager
- Site: [https://rvm.io/](https://rvm.io/)
- `\curl -sSL https://get.rvm.io | bash -s stable`

# Tips & Cheatsheets & Cool Docs
* Markdown Cheatsheet: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* SSH Cheatsheet: [https://gist.github.com/bradtraversy/f03df587f2323b50beb4250520089a9e](https://gist.github.com/bradtraversy/f03df587f2323b50beb4250520089a9e)
* Full-stack web dev notes: [https://github.com/8483/notes](https://github.com/8483/notes)
* Awesome Design Tools: [https://github.com/LisaDziuba/Awesome-Design-Tools](https://github.com/LisaDziuba/Awesome-Design-Tools)
* Women Made It: [https://github.com/LisaDziuba/Women-Made-It](https://github.com/LisaDziuba/Women-Made-It)
* Awesome Stacks: [https://github.com/stackshareio/awesome-stacks](https://github.com/stackshareio/awesome-stacks)
* Front-end Dev Handbook for 2019: [https://frontendmasters.com/books/front-end-handbook/2019/](https://frontendmasters.com/books/front-end-handbook/2019/) -- *SUPER AWESOME*
