---
layout: announcement
categories: [Release, 3.7.0]
title: Parrot 3.7.0 "Wanda" Released
---

> OTTO. Apes don't read philosophy.

> WANDA. Yes they do, Otto. They just don't understand it.
>   Now let me correct you on a couple of things, OK?
>   Aristotle was not Belgian. The central message of
>   Buddhism is not 'Every Man For Himself'.

> OTTO. You read...

> WANDA. And... the London Underground is not a political
>   movement. Those are all mistakes, Otto. I looked them up.

>   Now. You have just assaulted the one man who can keep you
>   out of jail and make you rich. So, what are you going to do
>   about it, huh? What would an intellectual do?
>   What would Plato do?

> -- A Fish Called Wanda, by John Cleese.

With that, I'd like to apologize for Parrot 3.7.0, also known as "Wanda". Parrot
is a virtual machine aimed at running all dynamic languages. Parrot 3.7.0 is
available on Parrot's FTP site, or by following the download instructions. For
those who would like to develop on Parrot, or help develop Parrot itself, we
recommend getting the latest and best Parrot code from github.

Parrot 3.7.0 News:

    - Core
     + Added mem_sys_strndup function.
     + Added new load_bytecode_p_s opcode as an eventual replacement for
    load_bytecode_s
     + Added new :tag() syntax to IMCC for PIR
     + Improved configuration support for msys
     + known-buggy parrot_debugger is no longer installed
    - Languages
     + Winxed
       - Updated snapshot to version 1.1.0
       - multi functions and methods
       - cast to var
       - load_packfile builtin
       - __NAMESPACE__ and __CLASS__ predefined constants
    - Documentation
       + The Archive::Tar and Archive::Zip libraries now have POD docs

The SHA256 message digests for the downloadable tarballs are:

    939d10eaeec7fdbe689a7e1cc6cd613e343b32eda0f5394b79f98347b68e37f8 parrot-3.7.0.tar.bz2
    494eb7749fbec101acaca890e1272c63192f274796a76463ffa42b99642b3e9b parrot-3.7.0.tar.gz

Many thanks to all our contributors for making this possible, and our sponsors
for supporting this project. The following people (in no particular
order) contributed to this release. Thanks!

Aaron Faanes, Allison Randal, Andrew Whitworth, Andy Dougherty, Andy
Lester, Bob Kuo, Christoph Otto, Will "Coke" Coleda, Dan Bolser,
Felipe Pena, Francois Perrad, Gerhard R, Jimmy Zhuo, Jonathan "Duke"
Leto, Jonathan Worthington, Martin von Gagern, Michael H. Hind, Moritz
Lenz, Peter Lobsinger, Jim Keenan, Kevin Polulak, Julian Albo

Our next scheduled release is 20 September, 2011.

Enjoy!
