- [README](#org2cd0480)
  - [Installation](#org8dd6004)
  - [Usage](#org12da0a0)


<a id="org2cd0480"></a>

# README

ox-bibtex-chinese is an extension of ox-bibtex, which can help chinese user to export bibliography to html.

![img](./snapshots/ox-bibtex-chinese.gif)


<a id="org8dd6004"></a>

## Installation

ox-bibtex-chinese is now available from the famous Emacs package repo [melpa](http://melpa.milkbox.net/), so the recommended way is to install it through Emacs package management system.


<a id="org12da0a0"></a>

## Usage

1.  Install bibtex2html to your system
2.  Configure Emacs

        (require 'org)
        (require 'ox-bibtex)
        (require 'ox-bibtex-chinese)
        (ox-bibtex-chinese-enable)
3.  See the format of "example/thesis.org" and try export it to html file.


Converted from ox-bibtex-chinese.el by [el2org](https://github.com/tumashu/el2org) .