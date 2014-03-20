# NOTICE: DEPRECIATED

This repository is **DEPRECIATED** in favor of the recent [ncclient](http://ncclient.grnet.gr/) version 0.4.1 that is now available in [PyPI](https://pypi.python.org/pypi/ncclient).  Please migrate your systems accordingly.

The Juniper/ncclient repository will remain online until June 1st, 2014.  After that date, this repository will be **REMOVED**.

ncclient: Python library for NETCONF clients
--------------------------------------------

`ncclient` is a Python library that facilitates client-side scripting
and application development around the NETCONF protocol. `ncclient` was
developed by [Shikar Bhushan](http://schmizz.net). It is now maintained
by [Leonidas Poulopoulos](http://ncclient.grnet.gr)

This is a [Juniper Networks](http://www.juniper.net) fork of `ncclient` based
off of [leopoul/ncclient v0.3.2](https://github.com/leopoul/ncclient)

Requirements:
* Python 2.6 <= version < 3.0
* setuptools 0.6+
* Paramiko 1.7+
* lxml 3.0+
* libxml2 (libxml2-dev on Ubuntu/Debian)
* libxslt (libxslt1-dev on Ubuntu/Debian)

Installation:

    [ncclient] $ sudo python setup.py install

Usage:

    [ncclient] $ python examples/juniper/*.py
