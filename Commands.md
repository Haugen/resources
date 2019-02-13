# Commands

Useful commands for miscellaneous things.

## npm

Updating to latest version of npm
`npm install npm@latest -g`

List all globally installed packages without their dependencies.
`npm list -g —depth=0`

Updating a single global package
`npm update -g <package_name>`

Updating all global packages
`npm update -g`

Removing a single global package
`npm uninstall -g <package_name>`

## n (Node version manager)

Installing the latest official release
`n latest`

Installing/Activating versions
`n 10.13.0`

Removing versions
`n rm 8.12.0`

## Homebrew

Homebrew cheat sheet: https://devhints.io/homebrew

List all installed packages, excluding dependencies
`brew leaves`

## VS Code

Smileys!!! 🐻
`cmd + ctrl + space`

## Git

Push a subfolder of a repository. Great for Heroku etc.
`git subtree push --prefix <folder> heroku master`
