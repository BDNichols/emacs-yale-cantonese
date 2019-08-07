# Emacs Yale Cantonese Input

Emacs Quail Cantonese input for Emacs using the Yale romanisation
system.  The original character list was generated using the word list
from CC-Canto (cccanto.org).

Yale is a common romanisation system for Cantonese which is intuitive
for English speakers and is widely used in textbooks.


## Installation

1. Move the `yale` directory (containing `yale.el`) to `~/.emacs.d/`
2. Add to your `.emacs` file:
```
  (add-to-list 'load-path "~/.emacs.d/yale/")
  (load "yale.el")
```

## Usage

In Emacs enter `C-x RET C-\ chinese-yale RET` to use the Yale input
method.  To toggle the current input method on or off use `C-\`.

