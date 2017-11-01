This is a mirror of http://www.vim.org/scripts/script.php?script_id=979

Idf.vim provides basic syntax support for EnergyPlus IDF files.

To use this file on a Mac, a new file was created in ~/.vim/syntax/ called Idf.vim and the text from the original repo was pasted into the new file. 

* The following lines must be in your .vimrc file 
    syntax on

* For file extension detection on loading, add the following to your .vimrc file
    "au BufRead,BufNewFile rc.log* set filetype=rclog
    au BufRead,BufNewFile *.idf setfiletype idf



