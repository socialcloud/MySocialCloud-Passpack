MySocialCloud Passpack
======================

About
-----
This is a modified version of [passpack.js](http://code.google.com/p/passpack/downloads/detail?name=passpack-v1.1.js&can=2&q=), standardized for MySocialCloud purposes.

None of the functionality, encryption/decryption mechanisms, or security protocols have changed since the original passpack.  The intention of these modifications are to update passpack to adhere to modern javascript standards.  There have been some additional functions added as a convenience.

What Has Changed
----------------

- Namespacing of all functions and variables
- Removed modifications of String prototype object
- Removed custom JSON parse and stringify functions and replaced with global JSON object's equivilant.
- Removed modifictions of Data prototype object, specifically the toJSON function.
- Added convenience functions for quickly encrypting and decrypting.
	- AES_ENCVAL
	- AES_DECVAL
	- SHA256_Encode
	- Base64Encode
	- Base64Decode

License
-------
**[MySocialCloud](https://mysocialcloud.com) Passpack** - 24, October 2012
This is a modified version of the original Passpack:
Host-Proof Hosting 1.0 library provided by Passpack Srl (www.passpack.com)

Both the [original source of Passpack](http://code.google.com/p/passpack/downloads/detail?name=passpack-v1.1.js&can=2&q=) as well as the included libraries may have been modified in this version. 
Dual licensed under the open source [MIT license](http://opensource.org/licenses/mit-license.html) and [LGPL license](http://www.gnu.org/licenses/lgpl.html), except where overridden by the following Passpack license.


----


**Passpack Host-Proof Hosting 1.0** - Rome, 22 june 2008
Copyright (c) 2008 Passpack Srl (www.passpack.com)
Dual licensed under the open source [MIT license](http://opensource.org/licenses/mit-license.html) and [LGPL license](http://www.gnu.org/licenses/lgpl.html), except where otherwise specified in the following.


Passpack Host-Proof Hosting includes pre-existent libraries, modified for the scope of this library:
 
----

**UTF-8 data encode / decode**
Base64 encode / decode
copyright http://www.webtoolkit.info/

----

**AES/Rijndael algorithm for 128/192/256-bit keys**
JavaScript implementation: Chris Veness, Movable Type Ltd: www.movable-type.co.uk
http://www.movable-type.co.uk/scripts/AES.html
Distributed under a [LGPL license](http://www.gnu.org/licenses/lgpl.html)

----

**'Block' Tiny Encryption Algorithm xxtea**
(c) 2002-2006 Chris Veness <scripts@movable-type.co.uk>
JavaScript implementation: Chris Veness, Movable Type Ltd: www.movable-type.co.uk
http://www.movable-type.co.uk/scripts/TEAblock.html
Distributed under a [LGPL license](http://www.gnu.org/licenses/lgpl.html)

----

**json2.js**, 2008-01-17
Distributed as [Public Domain](http://en.wikipedia.org/wiki/Public_domain) by Douglas Crockford
http://www.JSON.org/js.html

----

**A JavaScript implementation of the Secure Hash Algorithm, SHA-256**
Version 0.3 Copyright Angel Marin 2003-2004 - http://anmar.eu.org/
Distributed under the [BSD License](http://opensource.org/licenses/bsd-license.php)