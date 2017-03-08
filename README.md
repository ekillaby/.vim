# Config for vim
See also: http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/


Add the following to `~/.vimrc`.
```
" Pathogen
execute pathogen#infect()

" Editor settings
set number
set hlsearch
syntax on
filetype plugin indent on
set tabstop=2 shiftwidth=2 expandtab
set cursorline

" Colorschemes
"colorscheme tir_black
"colorscheme lettuce
colorscheme distinguished

" vim-go
let g:go_highlight_functions = 1
let g:go_highlight_methods = 1
let g:go_highlight_fields = 1
let g:go_highlight_types = 1
let g:go_highlight_operators = 1
let g:go_highlight_build_constraints = 1

```
