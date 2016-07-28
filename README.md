# Awesome DTrace [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome DTrace books, articles, videos, tools and resources.

![Pony](http://dtrace.org/blogs/wp-content/uploads/2011/11/dtracepony-120.png)

Layout inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome DTrace](#awesome-dtrace)
    - [Learn DTrace](#learn-dtrace)
        - [Books](#books)
        - [Other](#other)
    - [Articles](#articles)
        - [PID Provider](#pid-provider)
        - [USDT Provider](#usdt-provider)
        - [Sysevent Provider](#sysevent-provider)
    - [Videos](#videos)
        - [dtrace.conf](#dtraceconf)
    - [Software](#software)
        - [Programming languages](#programming-languages)
            - [Erlang](#erlang)
            - [Lua](#lua)
            - [node.js](#nodejs)
            - [Perl](#perl)
            - [PHP](#php)
            - [Python](#python)
            - [Ruby](#ruby)
        - [Databases](#databases)
        - [Webservers](#webservers)
    - [Tools](#tools)
    - [Community](#community)
    - [Contributing](#contributing)

- - -

## Learn DTrace

Recommended reading for learning DTrace.

### Books

- [Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) - illumos.org DTrace guide.
- [DTrace: Dynamic Tracing in Oracle Solaris, Mac OS X, and FreeBSD](http://www.dtracebook.com/index.php/Main_Page) - official DTrace book.
- [Dynamic Tracing with DTrace & SystemTap](http://myaut.github.io/dtrace-stap-book/) - a book introduces both DTrace and SystemTap.

### Other

- [dtrace(1m) man page](https://illumos.org/man/1m/dtrace) - DTrace manual page.
- [DTrace cheatsheet](http://www.brendangregg.com/DTrace/DTrace-cheatsheet.pdf) - DTrace cheatsheet by Brendan Gregg.
- [DTrace one-liners](http://www.brendangregg.com/DTrace/dtrace_oneliners.txt) - DTrace one liners. Handy commands.
- [DTrace one-liners (FreeBSD)](https://wiki.freebsd.org/DTrace/One-Liners) - DTrace one liners from FreeBSD.
- [DTrace QuickStart](http://www.tablespace.net/quicksheet/dtrace-quickstart.html) - DTrace quick starting guide.
- [Using DTrace stories](https://github.com/NanXiao/using-dtrace-stories) - A collection of using DTrace to debug system stories.

## Articles

Interesting articles about DTrace and real-world use cases.

### PID Provider

- [pid provider: entry probe](http://dtrace.org/blogs/brendan/2011/02/09/dtrace-pid-provider/) - DTrace pid Provider.
- [pid provider: entry arguments](http://dtrace.org/blogs/brendan/2011/02/11/dtrace-pid-provider-arguments/) - DTrace pid Provider Arguments.
- [pid provider: return](http://dtrace.org/blogs/brendan/2011/02/14/dtrace-pid-provider-return/) - DTrace pid Provider return.
- [pid provider: instructions](http://dtrace.org/blogs/brendan/2011/02/16/dtrace-pid-provider-instructions/) - DTrace pid Provider Instructions.
- [pid provider: overhead](http://dtrace.org/blogs/brendan/2011/02/18/dtrace-pid-provider-overhead/) - DTrace pid Provider Overhead.
- [pid provider exposed](http://dtrace.org/blogs/ahl/2005/03/01/pid-provider-exposed/) - pid providers internals by Adam Leventhal.
- [When magic collides](http://dtrace.org/blogs/bmc/2011/03/09/when-magic-collides/) - pid provider bug deep dive by Bryan Cantrill.

### USDT provider

- [Understanding DTrace ustack helpers](http://dtrace.org/blogs/dap/2013/11/20/understanding-dtrace-ustack-helpers/) - DTrace ustack helpers.
- [USDT Providers Redux](http://dtrace.org/blogs/dap/2011/12/13/usdt-providers-redux/) - reference for building USDT providers in custom applications.

### Sysevent provider

- [DTrace sysevent provider](https://blogs.oracle.com/eschrock/entry/dtrace_sysevent_provider) - Solaris/illumos sysevent provider for DTrace.

## Videos

Interesting videos about DTrace.

- [DTrace review](https://www.youtube.com/watch?v=TgmA48fILq8) - Bryan Cantrill explains how to significantly improve debugging both for development and live systems with DTrace.

### dtrace.conf

- [dtrace.conf 2008](https://youtu.be/RvyP61WeFdM?list=PL8516982CBF9FADCC)
    - [NFSv3 and iSCSI providers](https://www.youtube.com/watch?v=sgBCz7bXkSo&index=4&list=PL8516982CBF9FADCC)
    - [DTrace for hardware](https://www.youtube.com/watch?v=1Bc2Dz8aS6s&list=PL8516982CBF9FADCC&index=5)
    - [Zones & DTrace](https://www.youtube.com/watch?v=D8_onK0pSvA&index=8&list=PL8516982CBF9FADCC)
    - [DTracing a Solaris build](https://www.youtube.com/watch?v=e55iXXYj-74&index=10&list=PL8516982CBF9FADCC)
    - [War Stories](https://www.youtube.com/watch?v=yR39YqVXQOM&index=11&list=PL8516982CBF9FADCC)
    - [Sun Benchmarks](https://www.youtube.com/watch?v=uK0DjEXo99w&list=PL8516982CBF9FADCC&index=12)
    - [Erlang](https://www.youtube.com/watch?v=PXIGE5GFAkE&index=13&list=PL8516982CBF9FADCC)
    - [Erlang (continued)](https://www.youtube.com/watch?v=YTNiCv9Za2Y&index=14&list=PL8516982CBF9FADCC)
    - [Instrumenting Adobe AIR](https://www.youtube.com/watch?v=4astU1_X5xM&index=15&list=PL8516982CBF9FADCC)
    - [HotSpot Runtime & Java](https://www.youtube.com/watch?v=8kdJDHqiByI&list=PL8516982CBF9FADCC&index=16)
    - [PostgreSQL: Looking Under the Hood with Solaris](https://www.youtube.com/watch?v=p5NKcxDny_4&list=PL8516982CBF9FADCC&index=17)
    - [PostgreSQL Provider](https://www.youtube.com/watch?v=SJykRURWgeU&list=PL8516982CBF9FADCC&index=18)
    - [Distributed DTrace](https://www.youtube.com/watch?v=oYK1kgFwxk4&index=19&list=PL8516982CBF9FADCC)
    - [Apple Port of DTrace](https://www.youtube.com/watch?v=OKSuox4eFrk&list=PL8516982CBF9FADCC&index=21)

- [dtrace.conf 2012](https://www.youtube.com/watch?v=l_7v7Fn7uMQ&list=PL973D48F273EB0360)
    - [DTrace State of the Union](https://www.youtube.com/watch?v=l_7v7Fn7uMQ&list=PL973D48F273EB0360)
    - [User-Level CTF](https://www.youtube.com/watch?v=0QF04ivO_WE&list=PL973D48F273EB0360&index=3)
    - [Dynamic Translators](https://www.youtube.com/watch?v=CqLcj0lVnp4&index=4&list=PL973D48F273EB0360)
    - [Clang Parser for DTrace](https://www.youtube.com/watch?v=6NqV_Uj8Ba4&index=7&list=PL973D48F273EB0360)
    - [Visualizations](https://www.youtube.com/watch?v=XD5hdaWnQM4&index=8&list=PL973D48F273EB0360)
    - [Visualizations, Enabling Toolchain for Seamless USDT](https://www.youtube.com/watch?v=3Sqa8mmtnMM&index=9&list=PL973D48F273EB0360)
    - [More Visualizations](https://www.youtube.com/watch?v=-B6u6wY3Iro&index=10&list=PL973D48F273EB0360)
    - [DTrace in node.js](https://www.youtube.com/watch?v=0ZMvSh7lUdM&list=PL973D48F273EB0360&index=11)
    - [DTrace and Erlang](https://www.youtube.com/watch?v=4Si-7nAic2c&list=PL973D48F273EB0360&index=12)
    - [DTrace on Linux](https://www.youtube.com/watch?v=NElog3MvUC8&list=PL973D48F273EB0360&index=13)
    - [ZFS Provider](https://www.youtube.com/watch?v=m_V7yrrn49Y&index=14&list=PL973D48F273EB0360)
    - [DTrace on FreeBSD](https://www.youtube.com/watch?v=s5PpSiPfSNI&index=15&list=PL973D48F273EB0360)
    - [Barriers to DTrace Adoption](https://www.youtube.com/watch?v=P95LHZ-WOWw&index=16&list=PL973D48F273EB0360)

- [dtrace.conf 2016](https://www.joyent.com/about/events/2016/dtrace-conf)

## Software

List of software with DTrace support.

### Programming languages

#### Erlang

- [Erlang](http://erlang.org/doc/apps/runtime_tools/DTRACE.html) - DTrace and Erlang/OTP.

#### Lua

- [lua-usdt](https://github.com/chrisa/lua-usdt) - libusdt bindings for Lua.

#### node.js

- [node-dtrace-provider](https://github.com/chrisa/node-dtrace-provider) - Native DTrace probes for node.js apps.

#### Perl

- [perl-Devel-DTrace-Provider](https://github.com/chrisa/perl-Devel-DTrace-Provider) - Perl wrapper for libusdt.

#### PHP

- [PHP](https://secure.php.net/manual/en/features.dtrace.dtrace.php) - Using PHP and DTrace.

#### Python

- [Python](https://www.jcea.es/artic/python_dtrace.htm) - DTrace patch for Python 2.7.x and 3.x.
- [python-usdt](https://github.com/nshalman/python-usdt) - libusdt bindings for Python.

#### Ruby

- [Ruby](http://ruby-doc.org/core-2.3.1/doc/dtrace_probes_rdoc.html) - Ruby DTrace probes.
- [ruby-usdt](https://github.com/kevinykchan/ruby-usdt) - Native DTrace probes for ruby apps.

### Databases

- [MySQL](https://dev.mysql.com/doc/refman/5.7/en/dba-dtrace-mysqld-ref.html) - MySQL DTrace probes.
- [PostgreSQL](https://www.postgresql.org/docs/current/static/dynamic-trace.html) - PostgreSQL DTrace probes.

### Webservers

- [mod_usdt](https://github.com/davepacheco/mod_usdt) - "httpd" DTrace provider.

## Tools

- [DTraceToolkit](http://www.brendangregg.com/dtracetoolkit.html) - a collection of useful documented DTrace scripts.
- [dtrace-cloud-tools](https://github.com/brendangregg/dtrace-cloud-tools) - DTrace tools written for the SmartOS/SmartDataCenter cloud (illumos-based).
- [pgsql tools](https://github.com/joyent/pgsqlstat) - report top-level PostgreSQL stats.
- [portsnoop](https://github.com/davepacheco/portsnoop) - trace event port activity.
- [storage tools](https://github.com/richardelling/tools) - report NFS, CIFS and iSCSI stats.

## Community

- [Community site](http://dtrace.org) - DTrace community site.
- [Mailing list](http://dtrace.org/blogs/mailing-list/) - DTrace community mailing list.
- [China DTrace](http://chinadtrace.org/) - A Chinese DTrace site.

## Contributing

Contributions are more than welcome! Please see [contribution guidelines](https://github.com/xen0l/awesome-dtrace/blob/master/CONTRIBUTING.md) first.
