# AMPL package for Sublime Text 2

Provides syntax highlighting for the AMPL modelling language (`.mod`, `.dat` and `.run` files).

## Installation

**Using Sublime Package Control** (recommended): If you have installed [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install the AMPL Language package via the `Package Control: Install Package` menu item (shortcut: **CTRL+SHIFT+P**). Search for `AMPL Highlighting` in the list.

**Without Git:** Download the latest source zip from [github](https://github.com/jackdunnnz/sublime-ampl/tarball/master) and extract the files to your Sublime Text "Packages" directory, into a new directory named *AMPL*.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/jackdunnnz/sublime-ampl.git AMPL

The "Packages" directory is located at:

* OS X:
    `~/Library/Application Support/Sublime Text 2/Packages/`
* Linux:
    `~/.Sublime Text 2/Packages/`
* Windows:
    `%APPDATA%/Sublime Text 2/Packages/`

You can access it through the menu in `Preferences` > `Browse Packages...`

## AMPL language

AMPL, an acronym for "A Mathematical Programming Language", is an algebraic modelling language for describing and solving high-complexity problems for large-scale mathematical computation (i.e. large-scale optimization and scheduling-type problems).

AMPL is available from http://www.ampl.com/

## Features

This package adds syntax highlighting for all built-in functions, as well as strings, numeric values (including `Infinity`), and function arguments.

Comments are also highlighted. In AMPL, line comments are started by `#`, and block comments are delineated by `/*` `*/`.

To solve an AMPL model, `ctrl+B` (Build) will invoke AMPL on the `.run` file for the model. This can be done from any of the files for the model, provided that the `.run` script shares the same name as the current file e.g. building `example.mod` would invoke AMPL on `example.run`.

## Support

This package is a port of the AMPL highlighting scheme for VIM. If there are any issues or suggestions to do with the highlighting, please let me know.
