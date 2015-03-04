---
layout: post
title: "Monitoring Driven Development"
date: "2015-03-04 09:51:37 -0600"
---
# Monitoring is the Same as Testing

These days, I'm called a "software developer".  While I have some background
doing test-driven development in C++ and OO-Perl, this is the first time I've
carried the "developer" job description exclusively.

When folks ask, I always say that I'm a "Recovering Sysadmin", a quip I got
from [Irving Popovetsky](https://www.chef.io/blog/author/irving/) at Chef.

There is some benefit to having a sysadmin background.  One thing I've noticed
is that developers love to test during development, but not once the code is
released.  With my team, I have been making the case that monitoring is the
same as testing.  If a test is important enough for TDD, then that same test
should be run **continuously** in the production environment.

Benji Weber takes the idea to its logical conclusion by proposing

## [Monitoring Driven Development](http://benjiweber.co.uk/blog/2015/03/02/monitoring-check-smells/)

*Sounds like a good idea to me.*

