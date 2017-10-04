# add acl module based on memcached-1.4.39
# modify file list
  update: memcached.c util.c util.h
  rename: flushall -> hcmd_flush_all
