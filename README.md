# vimrc
                                                                                                                                                                                       
runtime! debian.vim                                                                                                                                                                                                                         
                                                                                                                                                                                                                     
                                                                                                                                                                                                                                            
filetype plugin indent on                                                                                                                                                                                                                   
                                                                                                                                                                                                                         
                                                                                                                                                                                                                                            
set nobackup       "no backup files                                                                                                                                                                                                         
set noundofile     "no undo files                                                                                                                                                                                                           
set nowritebackup  "only in case you don't want a backup file while editing                                                                                                                                                                 
set noswapfile     "no swap files                                                                                                                                                                                                           
                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                            
syntax on                                                                                                                                                                                                                                   
set nu                                                                                                                                                                                                                                      
set relativenumber                                                                                                                                                                                                                          
set autoindent                                                                                                                                                                                                                              
set shiftwidth=4                                                                                                                                                                                                                            
set tabstop=4                                                                                                                                                                                                                               
set splitright                                                                                                                                                                                                                              
set scrolloff=999                                                                                                                                                                                                                           
set autoread                                                                                                                                                                                                                                
colorscheme habamax                                                                                                                                                                                                                         
set background=dark                                                                                                                                                                                                                         
set showmatch       " Show matching brackets.                                                                                                                                                                                               
                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                            
                                                                                                                                                                                                                                            
map <F1> :e ~/.vimrc<cr>                                                                                                                                                                                                                    
map <F2> :only<cr>:!gcc % -o %.f 2>out<cr>:vs out<cr><C-w>w                                                                                                                                                                                 
map <f3> :!./%.f<cr> 
