# vimrc

```
syntax on
set ts=4
set number
set hlsearch
set pastetoggle=<F10>
set ruler
set expandtab
set incsearch
set shiftwidth=4
set backspace=indent,eol,start 
highlight StatusLine guifg=SlateBlue guibg=Yellow
highlight StatusLineNC guifg=Gray guibg=White
set showmatch
set ignorecase
set formatoptions=tcrqn
set autoindent
set smartindent
set cindent
let g:neocomplcache_enable_at_startup = 1 
if &term=="xterm"
  set t_Co=8
  set t_Sb=^[[4%dm
  set t_Sf=^[[3%dm
endif
```
