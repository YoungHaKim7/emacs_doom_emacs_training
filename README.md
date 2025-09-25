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

```bash
nitializing profile bootstrapper...
! No profile loader found. Generating one...
  > Regenerating it...
> Synchronizing 1 known profile...
  - Added safe-mode
  ✓ Regenerated profile loader: ~/.local/share/doom/profiles.30.el
> Synchronizing default profile...
  > (Re)building profile in ~/.emacs.d/.local/etc/@/...
    > Generating 5 init files...
    ✓ Built init.30.2.el
> Deploying commit-msg and pre-push git hooks
  ✓ Created ~/.emacs.d/.git/hooks/commit-msg
  ✓ Created ~/.emacs.d/.git/hooks/pre-push
✓ Finished! Doom is ready to go!

But before you doom yourself, here are some things you should know:

1. Don't forget to run 'doom sync' and restart Emacs after modifying init.el or
   packages.el in ~/.config/doom. This is never necessary for config.el.

2. If something goes wrong, run `doom doctor` to diagnose common issues with
   your environment, setup, and config.

3. Use 'doom upgrade' to update Doom. Doing it any other way will require
   additional steps (see 'doom help upgrade').

4. Access Doom's documentation from within Emacs via 'SPC h d h' or 'C-h d h'
   (or 'M-x doom/help').

Have fun!

✓ Finished in 4m 22s
```
