# emacs_doom_emacs_training
https://github.com/doomemacs/doomemacs


# macOS 설치 (M1 기준)
- [210209_Getting Started with Emacs & Doom in 2021 (on Apple Silicon M1) · Emacs Doomcasts 27 | Zaiste Programming](https://youtu.be/eyYxuIGF8-g?si=PUupaRbMohU7UF3X)

- https://github.com/d12frosted/homebrew-emacs-plus

```bash
brew tap d12frosted/emacs-plus

brew install emacs-plus --HEAD --with-modern-doom3-icon
```

```bash
$ brew tap d12frosted/emacs-plus
$ brew install emacs-plus    [options] # install the latest release (Emacs 30)
$ brew install emacs-plus@31 [options] # install Emacs 31 (master)
$ brew install emacs-plus@30 [options] # install Emacs 30 (emacs-30)
$ brew install emacs-plus@29 [options] # install Emacs 29
```


```bash
brew install emacs

==> Caveats
To start emacs now and restart at login:
  brew services start emacs
Or, if you don't want/need a background service you can just run:
  /opt/homebrew/opt/emacs/bin/emacs --fg-daemon
==> Summary

# dependencies

$ brew install git ripgrep coreutils fd

$ git clone https://github.com/hlissner/doom-emacs ~/.emacs.d

$ bin/doom install


```
