Vim setting files for PRISM
===========================

Note that this vim setting files for PRISM is originally from [PRISM WebSite](http://www.prismmodelchecker.org/).

The purpose of this repository is to make easier to introduce PRISM settings using tools such as Vundle, NeoBundle and so on.

### Credits
- Marta Kwiatkowska et al. (The files `syntax/*` are the very things that they contribute)
- SHiNKA(@shinka_cb) (Repository Maintainer)

### Installation
- Using [NeoBundle](https://github.com/Shougo/neobundle.vim),
  add this line to your `.vimrc`

```vim
NeoBundleLazy 'shinka-cb/prism_vim', {'autoload':{'filetypes':['prismmodel', 'prismproperty']}}
```

- Using [Vundle](https://github.com/gmarik/vundle),
  add this line to your `.vimrc`

```vim
Bundle 'shinka-cb/prism_vim'
```

### License
The same as original prism syntax highlighting files (i.e., GPL2). 

