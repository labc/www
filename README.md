LAB Center's Website
====================

This contains the configuration, dependency, and linking information for the
LAB Center website.

Dependencies
------------

Seeing as the dependencies of an entire web app are non-trivial, this attempts 
to document them.

Some dependencies are included as git submodules:
* Django
* mongoengine
* (athens)

The following daemons are required:
* nginx
* memcached
* PostgreSQL
* MongoDB
* nginx-gridfs, gridfs-fuse, gridfsfusepy, or another solution to serve files 
  out of GridFS

The following libraries are required (listed as Ubuntu package names):
* python-pymongo
* python-gridfs
* python-psycopg2
* python-memcached

Configuration
-------------

TODO: Write this
