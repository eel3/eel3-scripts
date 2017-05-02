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
  * ahaf(1) : Python 2.7
  * ce(1) : Ruby 2.0.x
  * cew(1) : [Open usp Tukubai](https://github.com/usp-engineers-community/Open-usp-Tukubai "Open usp Tukubai")
  * deadlink(1) : Perl 5
  * dumpwav(1) : Python 2.7
  * extpcm(1) : Python 2.7
  * funcname(1) : Exuberant Ctags
  * mdc(1) : Node.js, [marked](https://github.com/chjj/marked "marked")
  * myindent(1) : [Artistic Style](http://astyle.sourceforge.net/ "Artistic Style"), Perl 5
  * udprecv(1) : Python 2.7
  * udpsend(1) : Python 2.7
  * linux/myipaddr(1) : ifconfig(8) (on CentOS 7, you must install *net-tools*)
  * linux/writeimg(1) : bzcat(1), gunzip(1), lzcat(1), xzcat(1)
3. Put all scripts and Makefile in a directory registered in PATH.
4. Execute make(1) for creating symlink to environment-dependent scripts.

| Environment             | target of make |
|:------------------------|:---------------|
| Linux                   | linux          |
| Mac OS X                | mac            |
| Raspbian (Raspberry Pi) | raspbian       |

Usage
-----

Please check help message `<script-file-name> -h`, or read scripts.
