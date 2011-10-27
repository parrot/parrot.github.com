---
layout: announcement
categories: [Release, 3.9.0]
title: Parrot 3.9.0 "Archaeopteryx" Released
---

On behalf of the Parrot team, I'm proud to announce Parrot 3.9.0 "Archaeopteryx".
[Parrot](http://parrot.org/) is a virtual machine aimed at running all dynamic
languages. Parrot 3.9.0 is available on
[Parrot's FTP site](ftp://ftp.parrot.org/pub/parrot/releases/supported/3.9.0/),
or by following the download instructions at
[http://parrot.org/download](http://parrot.org/download). For those who would
like to develop on Parrot, or help develop Parrot itself, we recommend using Git
to retrieve the source code to get the latest and best Parrot code.

Parrot 3.9.0 News:

    - Core
        + The whiteknight/kill_threads branch was merged, which removes the old and broken
        thread/concurrency implementation. Better and more flexible concurrency primitives
        are currently being worked on. This also involved removing some of the last vestiges
        of assembly code from Parrot as well as removing the share and share_ro vtables.
        + random_lib.pir was removed, since better alternatives already exist
        + The freeze and thaw vtables were removed from Default PMC, because they weren't
          useful and caused hard-to-find bugs.
        + A new subroutine profiling runcore was added. It can be enabled with the command-line
        argument of -R subprof . The resulting data can be analyzed with kcachegrind.
        + Added get_string VTABLE to FixedIntegerArray and FixedFloatArray PMCs
        + The update() method was added to the Hash PMC, which updates one Hash with the contents
          of another. This speeds up rakudo/nqp startup time.
    - Languages
        + Winxed
          - Updated snapshot to version 1.3.0
          - Added the builtin sleep
          - Modifier 'multi' allows some more multi functionality
    - Community
        + New repo for the Parrot Alternate Compiler Toolkit, a re-implementation of
          PCT in Winxed: https://github.com/parrot/PACT
    - Documentation
        + We are in the process to migrating our Trac wiki at http://trac.parrot.org/ to Github
          at https://github.com/parrot/parrot/wiki
        + Packfile PMC documentation was updated
    - Tests
        + Select PMC tests improved to pass on non-Linuxy platforms

The SHA256 message digests for the downloadable tarballs are:

    923b5ef403c26dd94c04127940659aea94516f79243a80de65fbababff44bfad parrot-3.9.0.tar.bz2
    568bfffad0bc7595164f342cd39c33ac967286423844491e85a8f9767f15871c parrot-3.9.0.tar.gz

Many thanks to all our contributors for making this possible. This release
comprises 182 commits by 17 authors on the master branch since the previous
release: Michael Schroeder, Whiteknight, soh_cah_toa, Jonathan "Duke" Leto,
Brian Gernhardt, Andy Lester, Christoph Otto, Peter Lobsinger, jkeenan, NotFound,
Jimmy Zhuo, Stefan Seifert, Andrew Whitworth, Francois Perrad, Moritz Lenz,
Tadeusz Sośnierz, gerd

Our next scheduled release is 15 November 2011.

Enjoy and may the force be with you!
