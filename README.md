# VSCode Settings

_Commands assume you running MacOS_

## Font

Install [Fira Code](https://github.com/tonsky/FiraCode/wiki/Installing)

## Settings

Symlink `settings.json` to your local settings.

```bash
ln -sF ${PWD}/settings.json ~/Library/Application\ Support/Code/User/settings.json
```

## Extensions

#### 1. Get the most recent version of the installed plugins

_The following command extracts list of extensions and prefixes it with the vscode script to install and adds it to the clipboard_

```bash
code --list-extensions | xargs -L 1 echo code --install-extension | pbcopy
```

#### 2. Install the plugins

```
code --install-extension cssho.vscode-svgviewer
code --install-extension dbaeumer.vscode-eslint
code --install-extension DotJoshJohnson.xml
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension Gruntfuggly.todo-tree
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension kamikillerto.vscode-colorize
code --install-extension mikestead.dotenv
code --install-extension ms-azuretools.vscode-docker
code --install-extension Orta.vscode-jest
code --install-extension pflannery.vscode-versionlens
code --install-extension Prisma.vscode-graphql
code --install-extension silvenon.mdx
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension stylelint.vscode-stylelint
code --install-extension timonwong.shellcheck
code --install-extension vscode-icons-team.vscode-icons
code --install-extension wesbos.theme-cobalt2
code --install-extension wix.vscode-import-cost

```
