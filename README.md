Libmeas
=======

A measurement system for critical embedded systems.

About
-----

libmeas is a C library that provides a simple API to make measurements on any
kind of system (that support calling C functions), specially on critical
embedded systems that has hard time constraints, hence libmeas can help you to
measure time, make counts, and get information of other system resources.

libmeas can run on any POSIX platform, but patches for the Linux kernel are
provided to measure time with more accuracy.


How to Install
--------------

	$ ./configure
	$ make
	$ make install

Documentation will be saved into doc directory.


Author:
-------

libmeas was written and is maintained by Renê de Souza Pinto.

Copyright (C) 2009 Renê de Souza Pinto

Bugs:
-----

BUG's shall be reported to rene@renesp.com.br

