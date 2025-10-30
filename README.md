# NAME

App::ghmulti - Helps when using multiple Github accounts with SSH keys

# VERSION

Version 0.06

# SYNOPSIS

    use App::ghmulti;

    App::ghmulti->run();

or

    {
      local @ARGV = @my_args;
      App::ghmulti->run();
    }

# DESCRIPTION

Please read the documentation in the [ghmulti](https://metacpan.org/pod/ghmulti) program for more information.

**Note**: this module uses the **git** command line tool, so **git** must be
installed and available via `PATH`.

# BUGS

Please report any bugs or feature requests to `bug-app-ghmulti at rt.cpan.org`, or through
the web interface at [https://rt.cpan.org/NoAuth/ReportBug.html?Queue=App-ghmulti](https://rt.cpan.org/NoAuth/ReportBug.html?Queue=App-ghmulti).  I will be notified, and then you'll
automatically be notified of progress on your bug as I make changes.

# SEE ALSO

[ghmulti](https://metacpan.org/pod/ghmulti),
[Git::RemoteURL::Parse](https://metacpan.org/pod/Git%3A%3ARemoteURL%3A%3AParse),
[GitHub::Config::SSH::UserData](https://metacpan.org/pod/GitHub%3A%3AConfig%3A%3ASSH%3A%3AUserData)

# SUPPORT

You can find documentation for this module with the perldoc command.

    perldoc App::ghmulti

You can also look for information at:

- RT: CPAN's request tracker (report bugs here)

    [https://rt.cpan.org/NoAuth/Bugs.html?Dist=App-ghmulti](https://rt.cpan.org/NoAuth/Bugs.html?Dist=App-ghmulti)

- Search CPAN

    [https://metacpan.org/release/App-ghmulti](https://metacpan.org/release/App-ghmulti)

- GitHub Repository

    [https://github.com/klaus-rindfrey/perl-app-ghmulti](https://github.com/klaus-rindfrey/perl-app-ghmulti)

# ACKNOWLEDGEMENTS

Many thanks to Oanh Nguyen (oanhnn) for publishing this gist:
[https://gist.github.com/oanhnn/80a89405ab9023894df7](https://gist.github.com/oanhnn/80a89405ab9023894df7), and to everyone who
contributed in the comments.

# AUTHOR

Klaus Rindfrey, `<klausrin at cpan.org.eu>`

# LICENSE AND COPYRIGHT

This software is copyright (c) 2025 by Klaus Rindfrey.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
