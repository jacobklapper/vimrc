syntax on
set mouse=a
set number
set tabstop=4
set softtabstop=4
set expandtab
nore ; :
nore , ;
set incsearch
set hlsearch
nnoremap <silent> <Space> :nohlsearch<Bar>:echo<CR>
inoremap <Up>   <C-O>gk
inoremap <Down> <C-O>gj
nnoremap <Up>   gk
nnoremap <Down> gj
inoremap jk <esc>
