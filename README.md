```
                                             _           _______
                                            /.\\        /  ___  \_________  _
                ___     ___                 \_/ \       | /   \     ____  \/ |   _____   
               /   \   /   \                  \  \      | | O |  _________/\_|  /  | o\  
              |  _  | |  \ _|                  \--\     | \___/ /             _/  _/  /  
              | | | |  \  \                    | o |     \      \       /\   /.\ / | |   
              | |_| |  _\  \                   /--/       \  \\  \      \/\  \_//  | |   
              |  _  | |  \  |                 /  /         \  \\  \      \ \      /  |   
              |_| |_|  \___/                _/  /           \   _  \      \-\     |  o\_ 
                                           / \ /            |  /.\  |     |o|     /_____\
                 for Vim                  | o |_      _____/   \_/  |     /-/     |     |
               by Knosowski                \_/__|__  |____   ______/     / /      |_____|
                                           |___ ___\ |    \_____   |    /  |
                                            |  \__ |  \___________/     | o \__
                                            |______|  |           |     \______\
        industrial robot programming                  |           |      |     |
                                                      |___________|      |_____|
```
# kawasaki-as-for-vim

Vim plugins (syntax, indent and more) for Kawasaki AS language

## Introduction:

Kawasaki AS for [Vim][10] (7.4 or later) is a collection of Vim scripts to help
programming [Kawasaki industrial robots][9]. 

It provides
* syntax highlighting,
* indenting,
* support for commentary [vimscript #3695][7]


## Installation:

### Installation with [vim-plug][14]:  ~  

Put this in your .vimrc:  >

    call plug#begin('~/.vim/plugged')
      Plug 'KnoP-01/kawasaki-as-for-vim'
    call plug#end()

For the first installation run: >

    :PlugInstall

Update every once in a while with: >

    :PlugUpdate

### Manual installation:  ~  

Extract the most recent [release][1] and copy the folders 
`/doc`, `/ftdetect`, `/ftplugin`, `/indent` and `/syntax` 
into your `~/.vim/` or `%USERPROFILE%\vimfiles\` directory. 
Overwrite kawasaki\_as.\* files from older installation. 

Put the following in your .vimrc: >

    syntax on                  " syntax and filetype on in that order
    filetype plugin indent on  " syntax and filetype on in that order

## Self promotion

If you like this plugin please Star it. If you don't but you think it could be
useful if this or that would be different, don't hesitate to email me or even
better open an [issue][5]. With a little luck and good timing you may find me
on ircs://irc.libera.chat:6697/#vim as KnoP in case you have any questions.  

[1]: https://github.com/KnoP-01/kawasaki-as-for-vim/releases/latest
<!-- [2]: https://github.com/KnoP-01/kawasaki-as-for-vim#FAQ -->
<!-- [3]: https://github.com/KnoP-01/kawasaki-as-for-vim/blob/master/doc/kawasaki-as.txt#L203 -->
<!-- [4]: https://www.vim.org/scripts/script.php?script_id=5348 -->
[5]: https://github.com/KnoP-01/kawasaki-as-for-vim/issues
[7]: https://github.com/tpope/vim-commentary
<!-- [8]: https://www.vim.org/scripts/script.php?script_id=39 -->
[9]: https://kawasakirobotics.com/products-robots/
[10]: https://www.vim.org/
<!-- [11]: https://github.com/andymass/vim-matchup -->
<!-- [12]: https://github.com/tpope/vim-endwise -->
[14]: https://github.com/junegunn/vim-plug
