# Power Query Mode for Emacs

Major mode that let's you edit the Power Query language in your favourite editor.

## Installation

### Manual installation
Just clone this repo to `emacs.d` and place the code below in your `init.el`:

``` emacs-lisp
(load "~/.emacs.d/power-query-mode/power-query-mode.el")
```

### Using [straight.el](https://github.com/raxod502/straight.el)
Place the code below in your `init.el`:

``` emacs-lisp
(straight-use-package
    '(power-query-mode :type git :host github :repo "fpvmorais/power-query-mode"))
```

