eel3-scripts
============

My miscellaneous scripts.

License
-------

CC0 1.0 Universal.

Target environments
-------------------

Cygwin, Linux, macOS.

Probably all scripts work on other Unix-like environment.

Set up
------

1. If you want to use all scripts, you must install some tools in the dependency.
    * ahaf(1) : Python 3.8.10 or higher
    * ce(1) : Ruby 2.0.x
    * cew(1) : [Open usp Tukubai](https://github.com/usp-engineers-community/Open-usp-Tukubai "Open usp Tukubai")
    * deadlink(1) : Perl 5
    * dumpwav(1) : Python 3.8.10 or higher
    * extpcm(1) : Python 3.8.10 or higher
    * extpcms(1) : Python 3.8.10 or higher
    * funcname(1) : Exuberant Ctags
    * mdc(1) : Node.js, [marked](https://github.com/chjj/marked "marked")
    * myindent(1) : [Artistic Style](http://astyle.sourceforge.net/ "Artistic Style"), Perl 5
    * tcpechoclient(1) : Python 3.8.10 or higher
    * tcpechoserver(1) : Python 3.8.10 or higher
    * udpechoclient(1) : Python 3.8.10 or higher
    * udpechoserver(1) : Python 3.8.10 or higher
    * udprecv(1) : Python 3.8.10 or higher
    * udpsend(1) : Python 3.8.10 or higher
    * linux/myipaddr(1) : ifconfig(8) (on CentOS 7, you must install *net-tools*)
    * linux/writeimg(1) : bzcat(1), gunzip(1), lzcat(1), unzip(1), xzcat(1)
2. Put all scripts and Makefile in a directory registered in PATH.
3. Execute make(1) for creating symlink to environment-dependent scripts.

| Environment             | target of make |
|:------------------------|:---------------|
| Linux                   | linux          |
| macOS                   | mac            |
| Raspbian (Raspberry Pi) | raspbian       |

Usage
-----

Please check help message `<script-file-name> -h`, or read scripts.
