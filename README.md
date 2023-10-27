# New Computer Setup 

This is the list of all the software needed to get a new development environment set up. Additionally, this folder has a `.zshrc` file with some custom aliases and configuration that helps bootstrap a new development environment. 


## Apps 

- General Purpose
  - [Firefox](https://www.mozilla.org/en-US/firefox/new/) 
  - [Spotify](https://www.spotify.com/us/download/other/)
- Dev Tools
  - [Homebrew](https://brew.sh/)
  - [XCode](https://developer.apple.com/xcode/) 
  - [OhMyZsh](https://ohmyz.sh/)
    - See .zshrc for recommended plugins to install
  - [iTerm2](https://iterm2.com/)
    - Import default profile found at `default-iterm2.json` in this project's root directory
  - [Postman](https://www.postman.com/downloads/?utm_source=postman-home) 
  - [Nvm](https://github.com/nvm-sh/nvm)  
  - [Docker](https://docs.docker.com/desktop/install/mac-install/)
  - Open API Tools
    - [Swagger CodeGen](https://github.com/swagger-api/swagger-codegen#getting-started)
    - [Swagger UI](https://github.com/swagger-api/swagger-ui/blob/master/docs/usage/installation.md)
  - [Pyenv](https://github.com/pyenv/pyenv#installation) 
    - [Related software for pyenv-build](https://github.com/pyenv/pyenv/wiki#suggested-build-environment)
  - [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) 
  - [VsCode & Extensions](https://code.visualstudio.com/) 
    - [Set up the Code command in your path](https://code.visualstudio.com/docs/setup/mac)
    - See the extensions [below](#vscode-extensions)
  - [Vue](https://cli.vuejs.org/guide/installation.html)
  - [Yarn](https://yarnpkg.com/) 
  - GNU Stuff?
    - [GNU sed](https://formulae.brew.sh/formula/gnu-sed)
    - [GNU coreutils](https://formulae.brew.sh/formula/coreutils)
  - [Set up SSH Keys for on GitHub](https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
- Communication Tools
  - [Slack](https://slack.com/) 
  - [Discord](https://discord.com/)
- Productivity Tools
  - [Bitwarden](https://bitwarden.com/)
    - [Bitwarden Shortcuts](https://bitwarden.com/help/keyboard-shortcuts/)
  - [Typora](https://typora.io/)
  - [Todoist](https://todoist.com/downloads) 
  - [Rectangle](https://rectangleapp.com/) 
  - Set up a folder as a default location for [screenshots](https://www.howtogeek.com/809107/where-do-screenshots-go-on-mac/)


## VSCode Extensions

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Spelling checker for source code
- [Debugger for Firefox](https://marketplace.visualstudio.com/items?itemName=firefox-devtools.vscode-firefox-debug)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Integrates ESLint JavaScript into VS Code
- [FHIR Tools](https://marketplace.visualstudio.com/items?itemName=Yannick-Lagger.vscode-fhir-tools): Run validation on the FHIR resources, ensuring the FHIR we extract is sensible.
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Git-itegration in the code editor
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
- [JavaScript and TypeScript Nightly](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next)
- [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest): Use Facebook's Jest With Pleasure
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv): Highlight CSV and TSV files, Run SQL-like queries
- [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [VSCode-Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons): Icons for Visual Studio Code

## General Commands
- `git config --global core.excludesfile ~/some/path/here/machine-setup/.gitignore`: link this project's gitignore for global usage 
- `git config --global user.name "Dylan Phelan"`
- `git config --global user.email "Dtphelan1@gmail.com"`
- Make sure you set up [tab navigation on your new mac](https://support.apple.com/en-us/HT204434#fullkeyboard), so you don't waste an hour wondering why you can't tab into anchor tabs. I.e. make sure you hit `Fn-Control-F7`
