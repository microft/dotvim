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

## References

https://vimawesome.com/
