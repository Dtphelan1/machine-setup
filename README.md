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
  - [iTerm2](https://iterm2.com/)
  - [Postman](https://www.postman.com/downloads/?utm_source=postman-home) 
  - [Nvm](https://github.com/nvm-sh/nvm)  
  - [Pyenv](https://github.com/pyenv/pyenv#installation) 
    - [Related software for pyenv-build](https://github.com/pyenv/pyenv/wiki#suggested-build-environment)
  - [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) 
  - [VsCode & Extensions](https://code.visualstudio.com/) 
    - [Set up the Code command in your path](https://code.visualstudio.com/docs/setup/mac)
    - See the extensions [below](#VSCode Extensions)
  - [Vue](https://cli.vuejs.org/guide/installation.html)
  - [Yarn](https://yarnpkg.com/) 
  - [Set up SSH Keys for on GitHub](https://docs.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
- Communication Tools
  - [Slack](https://slack.com/) 
  - [Discord](https://discord.com/)
- Productivity Tools
  - [Typora](https://typora.io/)
  - [Todoist](https://todoist.com/) 
  - [Bitwarden](https://bitwarden.com/)
    - [Bitwarden Shortcuts](https://bitwarden.com/help/keyboard-shortcuts/)
  - [Rectangle](https://rectangleapp.com/) 


## VSCode Extensions

- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker): Spelling checker for source code
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): Integrates ESLint JavaScript into VS Code
- [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest): Use Facebook's Jest With Pleasure
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): Git-itegration in the code editor
- [FHIR Tools](https://marketplace.visualstudio.com/items?itemName=Yannick-Lagger.vscode-fhir-tools): Run validation on the FHIR resources, ensuring the FHIR we extract is sensible.
- [VSCode-Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons): Icons for Visual Studio Code
- [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv): Highlight CSV and TSV files, Run SQL-like queries
- [Writing Markdown](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one): All you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more)
- [Markdown Lint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): Markdown linting and style checking for Visual Studio Code
- [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log): Automating the process of writing meaningful log messages.

## General Commands
- `git config --global core.excludesfile ~/some/path/here/machine-setup/.gitignore`: link this project's gitignore for global usage 
