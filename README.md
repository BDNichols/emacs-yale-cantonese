# Emacs Yale Cantonese Input

Emacs Quail Cantonese input for Emacs using the Yale romanisation
system.

Yale is a common romanisation system for Cantonese which is intuitive
to English speakers and is used in many textbooks.


## Installation

1. Move the `yale` directory (containing `yale.el`) to `~/.emacs.d/`
2. Add to your `.emacs` file:
```
  (add-to-list 'load-path "~/.emacs.d/yale/")
  (load "yale.el")
```

## Use

In Emacs enter `C-x RET C-\ chinese-yale RET` and type.  Use `C-\` to
toggle input method on and off.

