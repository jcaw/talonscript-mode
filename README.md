<h1 align=center>TalonScript-Mode</h1>
<p align=center>Major mode for interacting with `.talon` files from <a href=https://talonvoice.com/>Talon Voice</a>.</p>

<p align=center>(At the time of writing, .talon files are newapi only.)</p>

## Overview

This is currently a simple major mode. It just adds syntax highlighting and comment syntax.

## Installation & Usage

For now, clone this repo directly, make sure it's on the load-path, then:

```emacs-lisp
(require 'talonscript-mode)
```

`.talon` files will automatically open in `talonscript-mode`. 

Down the line I intend to add [Quelpa](https://github.com/quelpa/quelpa) compatibility but it won't work right now. I'll probably eventually get it on [MELPA](https://melpa.org/).
