# NAME

Full - simplify common boilerplate for Perl scripts and modules

# SYNOPSIS

    # in your script
    use Full::Script;
    # use strict, warnings, utf8 etc. are all now applied and in scope
    # or in a module that provides a class:
    use Full::Class;
    field $example;
    method example_method { return $example }

# DESCRIPTION

Perl has many modules and features, including some features which are somewhat discouraged
in recent code.

This module attempts to provide a good set of functionality for writing code without too
many lines of boilerplate. It has been extracted from [Myriad::Class](https://metacpan.org/pod/Myriad%3A%3AClass) so that it can be
used in other code without pulling in too many irrelevant dependencies.

For a list of Perl language features and modules applied by this,
please see:

- [Full::Pragmata](https://metacpan.org/pod/Full%3A%3APragmata) - base list
- [Full::Class](https://metacpan.org/pod/Full%3A%3AClass) - OO classes
- [Full::Script](https://metacpan.org/pod/Full%3A%3AScript) - `.pl` scripts

# SEE ALSO

There are many modules which provide similar functionality. Here are a few examples, in no particular
order:

- [Modern::Perl](https://metacpan.org/pod/Modern%3A%3APerl)
- [common::sense](https://metacpan.org/pod/common%3A%3Asense)

# AUTHOR

Original code can be found at https://github.com/deriv-com/perl-Myriad/tree/master/lib/Myriad/Class.pm,
by Deriv Group Services Ltd. `DERIV@cpan.org`. This version has been split out as a way to provide
similar functionality.

# LICENSE

Released under the same terms as Perl itself.
