---
title: Choosing a Text Editor
author: Troy Woodley
date: 2026-09-05
tags: [LaTeX, Programming, productivity]
---

A text editor is an indispensable tool for any workflow. A good text editor allows you to easily and fluidly edit all plaintext documents. In this article we compare and recommend text editors, with a primary focus on how they fit into a LaTeX workflow. All editors in this article are free, and most have permissive licences.

## Useful text editor features:

- Undo/redo 
- Search and replace
- syntax highlighting
- customizability
- spellcheck

#### Synctex: 

For LaTeX workflows, synctex is particularly useful. Synctex connects the lines of the `.tex` source file to the PDF output. If both your text editor and pdf viewer support synctex, you can search from any line in the `.tex` file to find where it is rendered in the PDF, as well as inverse search from any part of the PDF to find the appropriate part in the `.tex` file. Very useful!

### [neovim](neovim.io)/[vim](vim.org) 

| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✔       | ✔     | ✔         |

Neovim is highly recommended and is the text editor of choice for myself along with most of the UNIX club executive staff. Neovim's two main attractions are its unique keybinds, and its customizability. Vim keybinds are powerful and expressive. By combining keybinds, every desired action can be executed with only a few keystrokes, allowing for fast and fluid editing without you hands ever leaving the keyboard. Neovim/Vim allow the user to customize nearly every aspect of the editor. With a robust ecosystem of plugins as well as powerful scripting, you can make your vim your own.

#### NVIM vs VIM
Neovim is recommended over Vim. It is backwards compatible and more extensible, with Lua support. It preserves all Vim keybinds, so learning NVIM will enable you to use Vim as well. Vim comes with most distributions of Linux by default, so it is useful to be able to use while ssh-ing.

#### [vimtex](https://github.com/lervag/vimtex)

This is a very good LaTeX plugin for vim and neovim. It supports document compilation, a variety of PDF viewers, completion and synctex.

### [Emacs](https://www.gnu.org/savannah-checkouts/gnu/emacs/emacs.html)

| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✔       | ✔     | ✔         |

Emacs is the top competitor to neovim/vim. It is similarly free, and is equally customizable and extensible. It supports a large number of keyboard shortcuts, but relies on modifier keys rather than having a modal scheme like vim. You may find its keybinds more intuitive if you are switching over from other editors. Unlike vim it has non-text editing functionality such as email, calendar and IRC.

### [Nano](https://www.nano-editor.org/)

| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✔       | ✔     | ✔         |


Nano is a bare bones terminal based text editor, that comes pre-installed on many machines. It's UI is simple and intuitive, which makes it a good choice if you want to do something quick from the terminal and don't want to learn vim binds.

### [NotePad++](https://notepad-plus-plus.org/)

| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✔       | ✘     | ✘         |

Notepad++ is a lightweight GUI text editor for windows. It has all the basic functionality you need for light text editing and programming.

### [TextEdit]

| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✘       | ✔     | ✘         |

Similar to notepad, textedit is a lightweight GUI text editor. It comes default with MacOS, and is a good choice for light text editing and note taking. By default is uses rich text, but can be configured to use monospace fonts and write in plaintext. Does not support syntax highlighting, so not recommended for programming.

### [VSCode](https://code.visualstudio.com/) (and other IDEs)


| Windows | MacOS | GNU/Linux |
| ------- | ----- | --------- |
| ✔       | ✔     | ✔         |

Most IDEs have text editor functionality built in. VScode in particular also has a functional LaTeX plugin. However, it is unwieldy for general purpose text editing.
