slax_rt
=======

Nasty major modifications to Slax build scripts to add support for real-time Linux kernels

Usage
-----

Run `kernel.SlackBuild.rt` without arguments to get help. This will download, configure, compile and copy all the needed stuff to the given Slax directory (e.g. on a flash drive) automatically.

Notes
-----

This repository is a copy of the http://ftp.slax.org/Slax-7.x-development/sources/Slax-7.0-sources/kernel/ directory with modified scripts to exchange the bundled Linux kernel with its real-time version.

References
----------

*   [official howto](https://rt.wiki.kernel.org/index.php/RT_PREEMPT_HOWTO) on building of the `-rt` kernel (outdated, but you'll figure the right menuconfig options yourself - look at the `-rt` configs in this repository for inspiration)
