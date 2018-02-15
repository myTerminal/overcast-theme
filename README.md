# overcast-theme

[![Marmalade](https://img.shields.io/badge/marmalade-available-8A2A8B.svg)](https://marmalade-repo.org/packages/overcast-theme)  
[![License](https://img.shields.io/badge/LICENSE-GPL%20v3.0-blue.svg)](https://www.gnu.org/licenses/gpl.html)

A dark but vibrant color theme for Emacs

## Installation

### Manual

Save the file *overcast-theme.el* to disk and add the directory containing it to 'load-path' using a command in your '.emacs' file like:

    (add-to-list 'load-path "~/.emacs.d/")
    
The above line assumes that you've placed the file into the Emacs directory '.emacs.d'.

Activate the package with:

    (require 'overcast-theme)

### Marmalade

If you have Marmalade added as a repository to your Emacs, you can just install *overcast-theme* with

    M-x package-install overcast-theme RET

## Usage

Enable the theme by

    (load-theme 'overcast)

Alternatively, use

    (load-theme 'overcast
        t)

to avoid Emacs asking you for a confirmation before enabling the theme.

You might have to disable all themes that had been enabled earlier by

    (mapcar 'disable-theme
        custom-enabled-themes)

## Credits

This theme has been created using [ThemeCreator](https://github.com/mswift42/themecreator).
