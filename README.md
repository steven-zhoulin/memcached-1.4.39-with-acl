# add acl module based on memcached-1.4.39
* update: memcached.c util.c util.h
* rename: flushall -> hcmd_flush_all
* ./autogen.sh
* ./configure --prefix=/home/cache --with-libevent=/home/cache
* make
