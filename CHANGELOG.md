# Changelog

## v1.1.4

* [#2](https://github.com/pixl8/cbehcache/issues/2) Allow the use of CFML struct, query and array types for the 'ValueClass' for non-heap storage.

## v1.1.3

* [#1](https://github.com/pixl8/cbehcache/issues/1) Improve performance of cluster cache operations that potentially fail when the cache does not (yet) exist in the listening cluster node. Ignore missing caches and do not go to wirebox each time to fetch the cache.

## v1.1.2

* Fix for clear by key snippet not being possible (just have to clear all for now!)

## v1.1.1

* Fix for hardcoded path accidentally left in while local testing

## v1.1.0

* Added support for clustering using jGroups ([cbjgroups](https://github.com/pixl8/cbjgroups))

## v1.0.1

* Added support for `nonheap` and `disk` storage
* Added support for both `TTL` _and_ `TTI` expiry models
* Added working statistics
* Added documentation in README

## v0.1.1

* Build fixes

## v0.1.0

Initial proof of concept with with:

* Only Heapspace resource configurable
* Working with existing Coldbox cachebox provider config
* Timeouts not settable per individual entry
* No statistics
