# Custom Homebrew Vim tap

In [homebrew/core](https://github.com/Homebrew/homebrew-core) the version of Vim
that is built is `--without-x` or any other GUI option. The `unnamedplus`
register is only available via X11 (or similar).

Until
[homebrew/core#93064](https://github.com/Homebrew/homebrew-core/pull/93064) is
merged (if that ever happens) I'm using this tap.

## How do I install Vim with this?

`brew install jcla1/custom-vim-tap/vim`

