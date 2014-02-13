passhash
========

Javascript password hasher &amp; manager.

Eventually this will be more modular, but right now, it's all 
one page while I tinker with it.

NOTES:

1. Currently there's a hardcoded list of sites with weird password restrictions.   This can be stored separately, queries via ajax so that running pages get new versions without having to reload.

2. Firefox and IE can remember the master password.   Chrome cannot.   Whether you want to or not is up to you, but this restriction should be overcome.

TODO:

One JS file with configuration, loaded at start, rather than embedded in page (note 1).
One JS file with all management funcs rather than embedded in page.
Separate CSS file rather than embedded.

Config dicates hashing functions used, number of bits stored, 
and default output size (part of note 1).

Make it into an "app" that works on my stupid phone.

It's OK to centralize config settings with ajax+db .... just not the passwords!

Main site should link here:
http://passhash.com
