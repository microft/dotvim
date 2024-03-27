dotvim
======

my ~/.vim folder



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
