PyDbg
============

Overview
--------

Forked from [PyDbg](https://github.com/OpenRCE/pydbg). Pydasm.pyd is compiled with [gcc-mingw-4.3.3](http://beta-machon-lev.googlecode.com/files/gcc-mingw-4.3.3-setup.exe), and it's for python 2.7

Installation
------------

Rename the folder to pydbg and copy it to C:\Python27\Lib\. Remember, you need to use 32bit python.

Example
-------
	
	from pydbg import *
	from pydbg.defines import *
	
	dbg = pydbg()
	dbg.attach(pid)
	dbg.run()
	