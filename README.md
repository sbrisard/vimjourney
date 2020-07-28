# My journey into VIM land

## Location of files

### Under windows

```
VIMCONFIG = AppData/Local/nvim
VIMDATA = AppData/Local/nvim-data
```

## Installation of minpack

- Create the directory: `$VIMCONFIG/pack/minpac/opt`
- In this directory, clone the `minpac` repository: `git clone
  https://github.com/k-takata/minpac.git`

## Plugins that might be interesting

See [VimAwesome](https://vimawesome.com/).

- [fzf](https://github.com/junegunn/fzf.vim)
- [vim-surround](https://github.com/tpope/vim-surround)
- [ALE](https://github.com/w0rp/ale): ALE (Asynchronous Lint Engine) is a plugin
  providing linting (syntax checking and semantic errors) in NeoVim 0.2.0+ and
  Vim 8 while you edit your text files, and acts as a Vim Language Server
  Protocol client.
- [vim-bookmarks](https://github.com/mattesgroeger/vim-bookmarks): this vim
  plugin allows toggling bookmarks per line. A quickfix window gives access to
  all bookmarks. Annotations can be added as well. These are special bookmarks
  with a comment attached. They are useful for preparing code reviews. All
  bookmarks will be restored on the next startup.

<!-- Local Variables: -->
<!-- fill-column: 80 -->
<!-- End: -->
