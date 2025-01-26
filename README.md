# Almost Monochrome Themes for GNU Emacs

This is a fork of
[cryon/almost-mono-themes](https://github.com/cryon/almost-mono-themes)
which has been modified to satisfy my personal whims and preferences.

## Changes from upstream

- Removed the "cream" variant
- Tweaked colors
- Use "highlight" color as "hightlight" face
- Remove bold/italic from font-lock (syntax highlighting) faces

## Installation

Via [straight.el](https://github.com/radian-software/straight.el):

```lisp
(straight-use-package
 '(almost-mono-themes :type git :host github :repo "ixtenu/almost-mono-themes"))
;;(load-theme 'almost-mono-white t)
;;(load-theme 'almost-mono-gray t)
(load-theme 'almost-mono-black t)
```
