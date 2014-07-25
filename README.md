glim - 0.3.1
============

glim is the lightweight MC (Model, Controller) framework on top of werkzeug inspired from play & laravel. The aim is to build an architecture for API developers. So, there isn't any ui, view - related components. The development philosophy here is to make the core small as possible but still not featureless.

glim currently has
==================
- url routing w/ controller definitions
- filtering w/ controller definitions
- controller mapping with urls
- configuration module for different environments
- some command line utilities
- SQLAlchemy integration
- sql query builder in model layer
- an extension system that developers can integrate it to the base
  framework

glim will have
==============
- extension system that users can integrate into project dynamically
- commands module that enables easier to use command line utilities
- drivers for redis, memcache and some popular message queue services

glim is
=======
- lightweight
- build on top of werkzeug
- dependent on some great open source python projects (See reqs file)
- great for API development

glim isn't
==========
- full-stack
- stable currently
- django
- flask

tada
====

- add before & after handlers for app boot
- glim command-line tools
    + add new app
    + add new model
    + add new command
- improve extension system
    + command line functions to create extensions
- some nosql driver extensions
    + Memcached
- IoC implementation
- Mockery implementation
- Some other extensions to develop
    + Mail
    + Message Queue
    + Filesystem IO
- benchmarks & performance tests
    + apache bench
- testing
    + Mockery implementation
    + unit tests (maybe)
- coding standards & quality analysis (currently, a lot is hacking)
- documentation on first stable release
- package release for PyPI
