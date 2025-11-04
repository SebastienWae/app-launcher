> [!CAUTION]
> This repo is no longer maintained, use [emacs-exwm/xdg-launcher](https://github.com/emacs-exwm/xdg-launcher)

# app-launcher

`app-launcher` define the `app-launcher-run-app` command which uses Emacs standard completion feature to select an application installed on your machine and launch it.

## How to install with `straight.el`

```elisp
(straight-use-package
  '(app-launcher :type git :host github :repo "SebastienWae/app-launcher"))
```

Or if you are using `use-package` (thanks [@daviwil](https://github.com/daviwil))
```elisp
(use-package app-launcher
  :straight '(app-launcher :host github :repo "SebastienWae/app-launcher"))
```

## Credits
This package uses code from the [Counsel package](https://github.com/abo-abo/swiper) by Oleh Krehel.
