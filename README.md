py-pf2freebsd
=====

`py-pf` is a pure-Python module for managing OpenBSD's Packet Filter. `py-pf2freebsd` is a fork from `py-pf` which aims FreeBSD compatibility. It aims to add powerful and flexible scripting capabilities to PF, making integration with third-party software (like IDS, web-based configuration interfaces or custom management scripts) much easier.

It runs on Python 2.7, which is available through FreeBSD's [packages and ports system]


Installation
------------
Download the source code from [GitHub](https://github.com/dotpy/py-pf) and run
the install script:

    # python setup.py install


Tests
-----
To run the test suite, just run:

    # python setup.py test


`py-pf` Documentation
-------------
A detailed description of the PF module and its classes is available at
http://www.kernel-panic.it/programming/py-pf/.

A brief list of references, documentation and books about Python, OpenBSD and
Packet Filter can be found at
http://www.kernel-panic.it/software/py-pf/resources.html.


`py-pf` Credits
-------
Copyright (c) 2008-2016 Daniele Mazzocchio (danix@kernel-panic.it).

Licensed under BSD license (see LICENSE.md file).
