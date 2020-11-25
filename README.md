# GUACAMOLE_MicRedirect_FIX

Deply this pachee why i have spent one week to find resolv the RDP problem in the version 1.2.0 of Guacamole.
So... i found this post: https://github.com/apache/guacamole-server/pull/312#issuecomment-723833894&#010
"myjimmy" have resolv the problem and i decide to download your repository for resolv my problem but after installation not work.

So... I decide to read all documentation and understend why not work.

For funny try to match official guacamole source with "myjimmy" source, end boom! The pacchet work!

I'm very happy today! :-)

THe step for install correctly guacamole 1.2.0 are:

Download "guacamole-server-1.2.0_AUDIOMIC-FIX.tar.gz"
tar -xzf guacamole-server-1.2.0_AUDIOMIC-FIX.tar.gz
cd guacamole-server-1.2.0
./configure --with-init-dir=/etc/init.d
make
make install

ldconfig && cd ~

This work correctly and tested with "CentOS Linux release 8.2.2004 (Core)".


Heppy! :-D
