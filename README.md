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
==> Fetching downloads for: emacs
==> Downloading https://ghcr.io/v2/homebrew/core/emacs/manifests/30.2
################################################################################################################################################## 100.0%
==> Fetching emacs
==> Downloading https://ghcr.io/v2/homebrew/core/emacs/blobs/sha256:6fd75aed5b6ef68991921b6e61b001272310d572e9cc3b4945aff00dfc381f59
################################################################################################################################################## 100.0%
==> Pouring emacs--30.2.arm64_sequoia.bottle.tar.gz
==> Caveats
To start emacs now and restart at login:
  brew services start emacs
Or, if you don't want/need a background service you can just run:
  /opt/homebrew/opt/emacs/bin/emacs --fg-daemon
==> Summary
```
