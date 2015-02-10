eel3-scripts
============

My miscellaneous scripts.

License
-------

CC0 1.0 Universal.

Target environments
-------------------

Cygwin, Linux, Mac OS X.

Probably all scripts work on other Unix-like environment.

Set up
------

1. If you want to use all scripts, you must install some tools in the dependency.
  * deadlink(1) : Perl 5
  * funcname(1) : Exuberant Ctags
  * mdc(1) : Node.js, [marked](https://github.com/chjj/marked "marked")
3. Put all scripts and Makefile in a directory registered in PATH.
4. Execute make(1) for creating symlink to environment-dependent scripts.

| Environment             | target of make |
|:------------------------|:--------------:|
| Linux                   | linux          |
| Mac OS X                | mac            |
| Raspbian (Raspberry Pi) | raspbian       |

Usage
-----

Please check help message `<script-file-name> -h`, or read scripts.
