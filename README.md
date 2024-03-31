# dotvim

my ~/.vim folder


## Setup

in your ~/.vimrc you might want to add

```
set runtimepath+=~/.vim

execute pathogen#infect()

syntax on
colorscheme desert
filetype plugin indent on

autocmd VimEnter * NERDTree
nnoremap <leader>n :NERDTreeFocus<CR>
```
or copy over DOTvimrc.example

To pull all the submodules do
```
git submodule update --init --recursive
```

## References

https://vimawesome.com/
