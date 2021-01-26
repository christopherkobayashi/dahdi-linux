## What?

This is a fork of the official Digium/Sangoma dahdi-linux drivers.

## Why?

Digium has removed support for older analog cards (notably the TDM4x0 series) from their codebase.

People who have their older cards (or who have purchased Chinese clones from Taobao/AliExpress) are forced to use older versions of the drivers.  It appears that their philosophy is "if we're not making money off these cards, then nobody else should either".

Unfortunately, with the Linux device driver API being a constantly (and maddeningly) moving target, it isn't possible to compile older DAHDI drivers on recent kernels.

That's why this fork exists.  I've personally tested it with cards using the wctdm24xxp and wctdm drivers; others will probably work too.

Installation instructions are in the original README file in this directory.
