---
layout: announcement
categories: [Release, 3.8.0]
title: Parrot 3.8.0 "Magrathea" Released
---

On behalf of the Parrot team, I'm proud to announce Parrot 3.8.0, also known as
"Magrathea". [Parrot](http://parrot.org/) is a virtual machine aimed at running
all dynamic languages. Parrot 3.8.0 is available on
[Parrot's FTP site](ftp://ftp.parrot.org/pub/parrot/releases/devel/3.8.0/), or
by following the download instructions at http://parrot.org/download. For those
who would like to develop on Parrot, or help develop Parrot itself, we recommend
using Git to retrieve the source code to get the latest and best Parrot code.

Parrot 3.8.0 News:

    - Core
      + New tools/release/auto_release.pl script automates most of
        release
    - Languages
      + Winxed
        - Updated snapshot to version 1.2.0
        - allowtailcall modifier in try
        --debug command-line option, __DEBUG__ predefined constant
        and __ASSERT__ builtin
        - namespace, class, and ~ (bitwise not) operators
        - Implicit nested namespace in namespace and class
          declarations
        - -X command-line arg
    - Documentation
      + Improved release manager guide
    - Tests
      + New Makefile target "resubmit_smolder" to resubmit test
        results
      + New Makefile target "all_hll_test" runs the test suite of all
        HLLs and libraries known to work on Parrot
      + New Makefile target "interop_tests" run language
        interoperability tests, which runs as part of the normal "make
        test" as well

The SHA256 message digests for the downloadable tarballs are:

    f26d9c1a5d7723b1e778394f87f8bb993e188fb05a719a78eb0204612329cd75 parrot-3.8.0.tar.bz2
    ae10e52eaf150870949aa51c7588e3a09f8f0588c9e0a7a76c2201672b7c5c7a parrot-3.8.0.tar.gz

Many thanks to all our contributors for making this possible, and our sponsors
for supporting this project. Our next scheduled release is 18 October 2011.
Enjoy!

> Excerpt from The Hitchhiker's Guide to the Galaxy, page 634784, section 5a.
> Entry: Magrathea

> Far back in the mists of ancient time, in the great and glorious days of the
> former Galactic Empire, life was wild, rich and largely tax free. Mighty
> starships plied their way between exotic suns, seeking adventure and reward
> among the farthest reaches of Galactic space. In those days spirits were brave,
> the stakes were high, men were real men, women were real women and small furry
> creatures from Alpha Centauri were real small furry creatures from Alpha
> Centauri. And all dared to brave unknown terrors, to do mighty deeds, to boldly
> split infinitives that no man had split before – and thus was the Empire forged.
> Many men of course became extremely rich, but this was perfectly natural and
> nothing to be ashamed of because no one was really poor – at least no one worth
> speaking of. And for all the richest and most successful merchants life
> inevitably became rather dull and niggly, and they began to imagine that this
> was therefore the fault of the worlds they'd settled on. None of them was
> entirely satisfactory: either the climate wasn't quite right in the later part
> of the afternoon, or the day was half an hour too long, or the sea was exactly
> the wrong shade of pink.

> And thus were created the conditions for a staggering new form of specialist
> industry; custom-made luxury planet building. The home of this industry was the
> planet Magrathea, where hyperspatial engineers sucked matter through white holes
> in space to form it into dream planets – gold planets, platinum planets, soft
> rubber planets with lots of earthquakes – all lovingly made to meet the exacting
> standards that the Galaxy's richest men naturally came to expect.

> But so successful was this venture that Magrathea itself soon became the richest
> planet of all time and the rest of the Galaxy was reduced to abject poverty. And
> so the system broke down, the Empire collapsed, and a long sullen silence
> settled over a billion hungry worlds, disturbed only by the pen scratchings of
> scholars as they labored into the night over smug little treatises on the value
> of a planned political economy.

> Magrathea itself disappeared and its memory soon passed into the obscurity of
> legend.

> In these enlightened days, of course, no one believes a word of it.
