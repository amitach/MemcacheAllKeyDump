MemcacheAllKeyDump
==================

Run this script using ruby


The script will go through all the slabs by opening up a telnet connection and firing the cachedump on all slabs of memcache 
using a loop and thus fetching all keys from memcache, useful for debugging 
