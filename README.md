# HC-EMACS
**Work in progress**

## Migration list to emacs

Vim plugins:
1. File explorers:
* **scrooloose/nerdtree** - allows you to explore your filesystem and to open files and directories
    * **->** **name**: 
* **tpope/vim-vinegar** - enhances netrw(default Vim file explorer)
    * **->** **Emacs's Dired**:
        * **d**: Flag this file for deletion (dired-flag-file-deletion).
        * **u**: Remove the deletion flag (dired-unmark).
        * **<DEL>**: Move point to previous line and remove the deletion flag on that line (dired-unmark-backward).
        * **x**: Delete files flagged for deletion (dired-do-flagged-delete)
2. UI and visual code utilities:
* **vim-airline/vim-airline** - lean & mean status/tabline for Vim that's light as air
    * **->** **name**: 
* **vim-airline/vim-airline-themes** - themes for vim-airline
    * **->** **name**: 
* **ctrlpvim/ctrlp.vim** - full path fuzzy file, buffer, mru, tag, ... finder for Vim.
    * **->** **name**: 
* **tpope/vim-fugitive** - the best Git wrapper of all time
    * **->** **name**: 
* **airblade/vim-gitgutter** - shows a git diff in the 'gutter' (sign column)
    * **->** **name**: 
* **scrooloose/syntastic** - a syntax checking plugin for Vim
    * **->** **name**: 
* **Chiel92/vim-autoformat** - format code with one button press
    * **->** **name**: 
* **gregsexton/matchtag** - highlights the matching HTML tag when the cursor is positioned on a tag
    * **->** **name**: 
* **mattn/emmet-vim** - greatly improves HTML and CSS writing
    * **->** **name**: 
* **ap/vim-css-color** - highlights with colors the hexa CSS values and rgb and rgba color
    * **->** **name**: 
* **scrooloose/nerdcommenter** - to comment/uncomment multiple lines of code
    * **->** **Emacs's feature**: `M-;` to toggle comment-uncomment
* **arnaud-lb/vim-php-namespace** - for inserting "use" statements automatically
    * **->** **name**: 
* **craigemery/vim-autotag** - generate ctags when you save a file in a project with ctags generated
    * **->** **name**: 
3. Code autocomplition and snippets:
* **Valloric/YouCompleteMe** - YouCompleteMe is a fast, as-you-type, fuzzy-search code completion engine for Vim
    * **->** **name**: 
* **shawncplus/phpcomplete.vim** - improved PHP omni-completion. Based on the default phpcomplete.vim. Cohabits well with YouCompleteMe.
    * **->** **name**: 
* **dsawardekar/wordpress.vim** - provide auto-completions for wordpress PHP files
    * **->** **name**: 
* **SirVer/ultisnips** - UltiSnips is the ultimate solution for snippets in Vim. It has tons of features and is very fast
    * **->** **name**: 
* **honza/vim-snippets** - contains snippets files for various programming languages
    * **->** **name**: 
* **tpope/vim-surround** - surround.vim is all about "surroundings": parentheses, brackets, quotes, XML tags, and more
    * **->** **name**: 
* **spf13/vim-autoclose** - if you open a bracket, paren, brace, quote, etc, it automatically closes it
    * **->** **name**: 
4. Improved syntax:
* **sheerun/vim-polyglot** - syntax highlighting for every language
    * **->** **name**: 

## Emacs features from plugins

* **Projectile**
Commands:
    * `C-c p p`: Search project
    * `C-c p f`: Search file in project
    * `C-c p k`: Kill all buffers for project
    * `C-c p s g`: Run grep on the files in the project
    * `C-c p S`: Save all project buffers.
