---
layout: post
title: VIM configuration
category: unix
---

VIM is the king of plain text editor, especially on Linux and Mac.

    " General
        filetype plugin indent on   " ~/.vim/indent/ from http://goo.gl/pMmMw
        syntax on           " syntax highlighting
    
    " UI
        color pyte
        set guifont=Courier\ New:h18
        set cursorline      " highlight current line
        set backspace=indent,eol,start  " allow to delete before insertation
        set nu              " show line numbers
        set incsearch       " search as type
        set nohlsearch      " do not highlight search
        set ignorecase      " case insensitive search
        set scrolloff=5     " 5 lines at top/bottom
        set numberwidth=3   " Line number 0-999
        set cc=80           " highlight column 80
    
    " Formatting
        set shiftwidth=4    " use indents of 4 spaces
        set expandtab       " tabs are spaces
        set autoindent      " indent at the same level of the previous line
        set tabstop=4       " indent every four columns
        set nowrap          " wrap long lines
    
    " Mapping
        nnoremap ; :
        nnoremap j gj
        nnoremap k gk


