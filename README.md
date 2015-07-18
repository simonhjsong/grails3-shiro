Grails 3 Shiro Plugin
=====================

Grails 3 plugin for the Apache Shiro security framework.

Why another shiro plugin for Grails?
------------------------------------

The original plugin maintenance has stop for a while :
https://github.com/pledbrook/grails-shiro/issues/44

Status
------

* It compiles OK
* The unit tests pass OK

What has been done
------------------

While this is a work in progress, some things has been done :

* The original plugin was forked
* Initial migration using the grails 2 plugin `migrate2-grails3:0.3.2` to do the tedious work (thanks for it's author)
* Rewrite of `ShiroFilters` -> `ShiroInterceptor`
* Fix of broken imports
* Fix of broken tests

Left to do
----------

* Test with a grails 3 app
* Get more eye-balls to check, correct the code (hopefully you)

Goals
-----
* Short term: make this plugin work on Grails 3.x exactly as the original in Grails 2.x version
* Long term: evolve with Grails 3.x and shiro.

Disclaimer
----------

In its current status, it voids warranties, etc.
