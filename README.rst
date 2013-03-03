===============
raspbian-imager
===============

This is a collection of scripts that assist making operating system images for the Raspberry Pi from scratch, based on the Raspbian Linux distribution.

The Scripts
===========

raspbian-imager
---------------

This is the main script.

setup-repository
----------------

Sets up a Debian repository that is used as local mirror of Raspbian. The mirror is configured to only contain a minimal set of packages needed for package creation. Using this mirror does not only speed up repeated image creation, it also allows to ingest alternative versions or local builds of packages where needed.
