# Axis - Using `sqlite` to store key/command frequencies

*This project is taken from the [discussion](https://emacs-china.org/t/emacs-axis/30404)* on Emacs-China. All credits to the original poster [gynamics](https://emacs-china.org/badges/2/-?username=gynamics).

## Usage

```
(use-package axis
  :load-path "path/to/this/repo"
  :hook (after-init . global-axis-mode)
  ;; alternatively, do it in specific mode
  ;; :hook (prog-mode . axis-mode)
)
```