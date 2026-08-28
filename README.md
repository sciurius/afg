# App::File::Grepper

![Version](https://img.shields.io/github/v/release/sciurius//perl-App-File-Grepper)
![GitHub issues](https://img.shields.io/github/issues/sciurius//perl-App-File-Grepper)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
![Language Perl](https://img.shields.io/badge/Language-Perl-blue)

A simple but powerful tool to examine hierarchies of text files for
the occurrence of a pattern. Kind of recursive 'grep'.

A feature not present in similar tools is the ability to pass each
file that matches to less for viewing, or to vi or emacs for editing.

A simple driver script 'afg' is included for convenience.

# INSTALLATION

To install this module, run the following commands:

	perl Makefile.PL
	make
	make test
	make install


# SUPPORT AND DOCUMENTATION

Development of this module takes place on GitHub:
https://github.com/sciurius/perl-App-File-Grepper.

You can find documentation for this module with the perldoc command.

    perldoc App::File::Grepper

Please report any bugs or feature requests using the issue tracker on
GitHub.


# COPYRIGHT AND LICENCE

Copyright (C) 2012,2016,2022,2026 Johan Vromans

This program is free software; you can redistribute it and/or modify it
under the same terms as Perl itself.

