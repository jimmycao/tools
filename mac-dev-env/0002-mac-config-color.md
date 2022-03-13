# Mac配色
Mac配色涉及三个方面ls/iterm2/vim/，统一使用solarized方案
```
git clone git://github.com/altercation/solarized.git
```

## ls颜色
通过env看，如果是zsh，则编辑.zprofile文件
```
$ vi ~/.bash_profile  
export CLICOLOR=1
alias ll='ls -l'
```

## iterm2
到 solarized/iterm2-colors-solarized 下双击 Solarized Dark.itermcolors 和 Solarized Light.itermcolors 两个文件就可以把配置文件导入到 iTerm 里。

## Vim  (好像没什么用，直接去配置vim吧)
```
$ cd solarized
$ cd vim-colors-solarized/colors
$ mkdir -p ~/.vim/colors
$ cp solarized.vim ~/.vim/colors/

$ vi ~/.vimrc
syntax enable
set background=dark
colorscheme solarized
```