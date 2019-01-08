# NAME

clipboard\_to\_primary - sync XA\_CLIPBOARD to XA\_SELECTION X11 buffers

# SYNOPSIS

    clipboard_to_primary [OPTIONS]

# DESCRIPTION

I rarely use any gui application, the exception being firefox with
tridactyl. For some reason you can't paste from the PRIMARY buffer in
firefox/tridactyl without using the mouse (and at times that doesn't
work either). This solves this issue by syncing the CLIPBOARD buffer
with the content of the PRIMARY selection so you can use Shift+Insert to
paste in gui applications as well.

The clipboard buffer to use is \*\*hardcoded\*\* in the gtk source:
["https://unix.stackexchange.com/questions/178070/why-does-shiftinsert-paste-from-clipboard-in-some-applications-and-primary-in-o"](#https-unix-stackexchange-com-questions-178070-why-does-shiftinsert-paste-from-clipboard-in-some-applications-and-primary-in-o)

# OPTIONS

    -n,  --no-daemon  do not detach from the terminal

# AUTHOR

      \ \ | / /
       \ \ - /
        \ | /
        (O O)
        ( < )
        (-=-)

    Magnus Woldrich
    CPAN ID: WOLDRICH
    m@japh.se
    http://japh.se

# REPORTING BUGS

Report bugs to [m@japh.se](https://metacpan.org/pod/m@japh.se) or [use the issue tracker](http://github.com/trapd00r/clipboard_to_primary/issues).

clipboard\_to\_primary home page: [http://github.com/trapd00r/clipboard\_to\_primary/](http://github.com/trapd00r/clipboard_to_primary/)

# COPYRIGHT

Copyright 2018- the **clipboard\_to\_primary**s ["AUTHOR"](#author) and ["CONTRIBUTORS"](#contributors) as listed
above.

# LICENSE

This program is free software; you can redistribute it and/or modify it under
the same terms as Perl itself.
