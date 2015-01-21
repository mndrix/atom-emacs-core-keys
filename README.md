# Emacs Core Keys

Emacs key bindings for only core Atom functionality.

See the [list of supported keys](keymaps/emacs-core-keys.cson).


## Why?

There are several Atom packages which try to implement emacs functionality.  Unfortunately, they do too much and end up full of bugs and hard to maintain.

The most common GNU Emacs key bindings have a direct counterpart within Atom's core functionality. These can be implemented **without writing any CoffeeScript** and without relying on fragile Atom APIs.

## But ...

... I want a mark, a kill ring, `C-l` to recenter, incremental search, etc.

Most of those features are mutually independent.  They can be implemented as independent Atom packages so that users can pick and choose their favorites.
