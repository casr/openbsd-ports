OpenBSD Ports
=============

Mostly just some personal patches that are easier to maintain within
the ports system.

Once you have set up your ports collection [as per the instructions],
you can then:

    git clone https://github.com/casr/openbsd-ports /usr/ports/mystuff

    # then build the usual way. e.g.
    cd /usr/ports/mystuff/x11/dwm
    make
    doas make install

[as per the instructions]: http://www.openbsd.org/faq/ports/ports.html
