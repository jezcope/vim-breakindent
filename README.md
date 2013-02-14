# breakindent patch for vim

This is my fork of [Václav Šmilauer's breakindent patch for vim][patch 1], most recently [updated by Eli Carter][patch 2]. It causes wrapped lines to be indented to line up with the start of the line, which is quite useful when editing anything that has multiple levels of indent.

You probably just want the patch, but you can also clone this whole repository into a directory called `patches` in the root of a vim source code distribution and use [quilt][] to apply/manipulate the patch.

[patch 1]: http://www.mail-archive.com/vim-dev@vim.org/msg04076.html
[patch 2]: https://retracile.net/wiki/VimBreakIndent
[quilt]: http://savannah.nongnu.org/projects/quilt
