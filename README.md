# overcast-theme

[![MELPA-Stable](http://stable.melpa.org/packages/overcast-theme-badge.svg)](http://stable.melpa.org/#/overcast-theme)
[![MELPA](http://melpa.org/packages/overcast-theme-badge.svg)](http://melpa.org/#/overcast-theme)
[![Marmalade](https://img.shields.io/badge/marmalade-available-8A2A8B.svg)](https://marmalade-repo.org/packages/overcast-theme)  
[![License](https://img.shields.io/badge/LICENSE-GPL%20v3.0-blue.svg)](https://www.gnu.org/licenses/gpl.html)  
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y5E5GL7)

A dark but vibrant color theme for Emacs where almost everything except the code and the mode-line is muted so that the focus is entirely on buffer text. The mode-line for the active window is highlighted to make it more noticeable while moving back and forth between windows.

![Screenshot](images/screenshot.png)

## Installation

### Manual

Save the file *overcast-theme.el* to disk and add the directory containing it to 'load-path' using a command in your '.emacs' file like:

    (add-to-list 'load-path "~/.emacs.d/")
    
The above line assumes that you've placed the file into the Emacs directory '.emacs.d'.

Activate the package with:

    (require 'overcast-theme)

### MELPA-Stable / MELPA / Marmalade

If you have MELPA-Stable, MELPA or Marmalade added as a repository to your Emacs, you can just install *overcast-theme* with

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

Inspired by a template from [ThemeCreator](https://github.com/mswift42/themecreator).
