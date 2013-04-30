---
layout: default
active: about
title: Aura for PHP &#58; About
---

About Aura
==========

The Aura project provides independent library packages for PHP 5.4+. These
packages can be used alone, in concert with each other, or combined into a
full-stack framework of their own.

The Aura project is essentially the second major version of
[Solar](http://solarphp.com), reimagined and rewritten as a library collection
with dependency injection instead of a framework with service location. (The
name change from Solar to Aura is to reduce confusion with the Apache Solr
project.)


Libraries First, Framework Second
---------------------------------

The primary goal of Aura is to provide high-quality, well-tested,
[standards-compliant](http://php-fig.org), independent library packages that
can be used in any codebase. This means developers can use as much or as
little of the project as necessary.

In line with the goal of "libraries first", all packages are as self-contained
as possible and are independently downloadable. In some cases this level of
independence may lead to some class duplication between packages. In other
cases, it may lead to data-transfer objects being used to carry information
across package boundaries, so that the package can be used with non-Aura
codebases.

Aura has enough libraries to form a full-stack framework of its own. A system
repository is available to incorporate them all into a coherent framework for
application development. Note that the libraries were developed first, and
were not originally coupled to each other in a framework.

PHP 5.4+
--------

Aura is intended to take advantage of the features available in PHP 5.4+ (as
compared to PHP 5.2.x and prior). This means formal namespaces, anonymous
functions and closures, late static binding, short array syntax, traits, the
callable typehint, and other features not available in PHP 5.2.x and earlier.

