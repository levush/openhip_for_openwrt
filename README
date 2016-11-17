Host Identity Protocol implementation
=====================================

http://www.openhip.org/

OpenHIP is a BSD-licensed implementation of HIP v1 (RFC 5201) for Linux, Windows, and Mac. It runs in userspace leveraging the TUN/TAP driver.

Recently, development primarily focuses on Linux with these git branches:

  * _master/_  HIPv1 RFC 5201 and related specs
  * _feature/rfc7401_ - HIPv2 RFC 7401 and related specs


How to Build
------------

    ./bootstrap.sh
    ./configure
    make
    sudo make install


If you type "make install", the following files will be installed:

    /usr/local/sbin/hip
    /usr/local/sbin/hitgen
    /usr/local/sbin/hipstatus
    /usr/local/etc/hip/known_host_identities.xml

You'll also want to generate these files using the hitgen utility:

    /usr/local/etc/hip/my_host_identities.xml
    /usr/local/etc/hip/hip.conf


For full build and usage instructions, refer to the wiki:
http://www.openhip.org/wiki

More Info
---------
Release Notes can be found in the RELEASE_NOTES file.

The documentation for this implementation is maintained mainly on the wiki, but
previous documentation in HTML format can be found in the file named
doc/hipdoc.html.
