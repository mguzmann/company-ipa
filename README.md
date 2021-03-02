company-ipa
===========

![screencast](screencast-out.gif)

This package adds ipa completion for company.

This is a mirror, the official is over at: https://gitlab.com/mguzmann89/company-ipa/

Usage
=====

To install clone this package directly.

```emacs
(load-file "PATH/company-ipa.el")
```

Alternatively it should now be on MELPA.

After the package is installed, you can enable `company-ipa` by adding the following to your init file:

```emacs
(add-to-list 'company-backends 'company-ipa-symbols-unicode)
```

It is highly recomended that you use company-flx, otherwise completions will not work very well.

Use the variable `company-ipa-symbol-prefix` to change the prefix to trigger completion.
By default this is bound to `~pp`. You can change this with:

```emacs
(setq company-ipa-set-trigger-prefix "¬")
```
