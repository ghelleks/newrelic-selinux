newrelic-selinux
================

An SELinux policy for newrelic.

Usage
=====

As root (of course):

~~~~~~~~~~
# make -f /usr/share/selinux/devel/Makefile
# semodule -i newrelic.pp
~~~~~~~~~~

That's it.
