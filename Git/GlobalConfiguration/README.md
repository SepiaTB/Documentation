# Git GlobalConfiguration

The following code is used to change global-config settings

### `git config --global`

## User Name Configuration

### `git config --global user.name "Marc Jimenez"`

## E-mail configuration

### `git config --global user.email "email@gmail.com"`

## Core Editor configuration (VSCode)

### `git config --global core.editor "code --wait"`

## End of line configuration

When working with git we need to configure how we handle the end of lines.
To void compatibility problems if working in a group with different OS.
Should be set true --> Windows // false --> Linux / MacOS.

### `git config --global core.autocrlf true`

## Further Configuration

For further configuration (whether global or local).
Use the help command

### `git config --help`
