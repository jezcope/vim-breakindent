# breakindent patch for vim

This was my fork of [Václav Šmilauer's breakindent patch for vim][patch 1], most recently [updated by Eli Carter][patch 2]. It causes wrapped lines to be indented to line up with the start of the line, which is quite useful when editing anything that has multiple levels of indent.

Since vim 7.4.338 (released 25 June 2014) this has been [incorporated into the vim mainline][news], so the patch is no longer needed.  Just do `:he 'breakindent'` to find out more.

[patch 1]: http://www.mail-archive.com/vim-dev@vim.org/msg04076.html
[patch 2]: https://retracile.net/wiki/VimBreakIndent

[news]: https://retracile.net/blog/2014/07/18/18.00

