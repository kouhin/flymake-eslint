flymake-eslint.el
===============

An Emacs flymake handler for syntax-checking Javascript source code with linted with [eslint](http://eslint.org)

You may notice extreme similarity between this repo and a few of [@purcell](https://github.com/purcell) :)

Installation
=============

If you choose not to use one of the convenient packages in
[Melpa][melpa] and [Marmalade][marmalade], you'll need to add the
directory containing `flymake-eslint.el` to your `load-path`, and then
`(require 'flymake-eslint)`. You'll also need to install
[flymake-easy](https://github.com/purcell/flymake-easy).

Usage
=====

Add the following to your emacs init file:

    (require 'flymake-eslint)
    (add-hook 'js-mode-hook 'flymake-eslint-load) ;; or js2-mode-hook, perhaps


[marmalade]: http://marmalade-repo.org
[melpa]: http://melpa.org
