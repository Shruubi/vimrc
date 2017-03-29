# vimrc

This a repo containing my current `.vimrc` file.

### Basics

The starting point for this vimrc is [sensible.vim](https://github.com/tpope/vim-sensible) by Tim Pope. From there, I have added some configurations I have become accustomed to like `,` as my leader key and plugins that make my life easier.

### Plugins

I use NeoBundle as my plugin manager, and have the following plugins installed.

- scrooloose/nerdtree
- tpope/vim-fugitive
- ctrlpvim/ctrlp.vim
- airblade/vim-gitgutter
- jiangmiao/auto-pairs
- mattn/emmet-vim
- pangloss/vim-javascript
- mxw/vim-jsx
- tomasr/molokai

### Useful Remappings

```
Leader = ,
<Leader>e = run ctrlp
<Leader>b = ctrlp but for buffers
<C-n> = Toggle NerdTree
```

For the most part, I try to keep vim pretty standard in terms of keybindings and only use modified keybindings that I have become used to through using other peoples vimrc.

### License

Distributed under the same terms as Vim itself. See :help license.
