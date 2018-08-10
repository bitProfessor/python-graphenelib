Python Library for Graphene
===========================

![](https://img.shields.io/pypi/v/graphenelib.svg?style=for-the-badge)
![](https://img.shields.io/github/downloads/xeroc/python-graphenelib/total.svg?style=for-the-badge)
![](https://img.shields.io/pypi/pyversions/graphenelib.svg?style=for-the-badge)
![](https://img.shields.io/pypi/l/graphenelib.svg?style=for-the-badge)
![](https://cla-assistant.io/readme/badge/graphenelib/python-graphenelib)

**Stable**

[![Travis master](https://travis-ci.org/xeroc/python-graphenelib.png?branch=master)](https://travis-ci.org/xeroc/python-graphenelib)
[![docs master](https://readthedocs.org/projects/python-graphenelib/badge/?version=latest)](http://python-graphenelib.readthedocs.io/en/latest/)
[![codecov](https://codecov.io/gh/xeroc/python-graphenelib/branch/master/graph/badge.svg)](https://codecov.io/gh/xeroc/python-graphenelib)


**Develop**

[![Travis develop](https://travis-ci.org/xeroc/python-graphenelib.png?branch=develop)](https://travis-ci.org/xeroc/python-graphenelib)
[![docs develop](https://readthedocs.org/projects/python-graphenelib/badge/?version=develop)](http://python-graphenelib.readthedocs.io/en/develop/)
[![codecov develop](https://codecov.io/gh/xeroc/python-graphenelib/branch/develop/graph/badge.svg)](https://codecov.io/gh/xeroc/python-graphenelib)

Installation
------------

Install with `pip`:

    $ sudo apt-get install libffi-dev libssl-dev python-dev
    $ pip3 install graphenelib

Manual installation:

    $ git clone https://github.com/xeroc/python-graphenelib/
    $ cd python-graphenelib
    $ python3 setup.py install --user

Dependencies
------------

Some dependencies are not required for parts of the library to run
properly. However these modules require some additional libraries to be
present:

* `graphenebase.bip38`
   * `pycrypto==2.6.1`
   * `scrypt==0.7.1` (to speedup scrypt hashing)
* `graphenebase.memo`
   * `pycrypto==2.6.1`

Upgrade
-------

    $ pip install --user --upgrade graphenelib

Documentation
-------------

Thanks to readthedocs.io, the documentation can be viewed
[online](http://python-graphenelib.readthedocs.io/en/latest/)

Documentation is written with the help of sphinx and can be compile to
html with:

    cd docs
    make html

Licence
-------

MIT, see `LICENCE.txt`
