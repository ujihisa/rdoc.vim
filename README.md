# RDoc.Vim

## INSTALL

* Copy `syntax/rdoc.vim` on your systen as  `~/.vim/syntax/rdoc.vim`
  or just use this directly.
* Write `ftdetect/rdoc.vim` as the below:

        autocmd BufRead,BufNewFile *.rd,*.rdoc     set filetype=rdoc

    * (I tried to use it here but it didn't work)
