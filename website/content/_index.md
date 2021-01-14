---
date: 2017-10-19T15:26:15Z
lastmod: 2019-10-26T15:26:15Z
publishdate: 2018-11-23T15:26:15Z
---

<p align="center"><img src="includes/img/circt-logo.svg"/></p>

# ⚡️ "CIRCT" / Circuit IR Compilers and Tools

"CIRCT" stands for "Circuit IR Compilers and Tools".  One might also interpret
it as the recursively as "CIRCT IR Compiler and Tools".  The T can be
selectively expanded as Tool, Translator, Team, Technology, Target, Tree, Type,
... we're ok with the ambiguity.

The CIRCT community is an open and welcoming community.  If you'd like to
participate, you can do so in a number of different ways:

1) Join our [Discourse Forum](https://llvm.discourse.group/c/Projects-that-want-to-become-official-LLVM-Projects/circt/) on the LLVM Discourse server.  To get a "mailing list" like experience click the bell icon in the upper right and switch to "Watching".  It is also helpful to go to your Discourse profile, then the "emails" tab, and check "Enable mailing list mode".

2) Join our weekly video chat.  Please see the
[meeting notes document](https://docs.google.com/document/d/1fOSRdyZR2w75D87yU2Ma9h2-_lEPL4NxvhJGJd-s5pk/edit#)
for more information.

3) Contribute code.  CIRCT follows all of the LLVM Policies: you can create pull
   requests for the CIRCT repository, and gain commit access using the [standard
   LLVM policies](https://llvm.discourse.group/c/Projects-that-want-to-become-official-LLVM-Projects/circt/).

Also take a look at the following diagram, which gives a brief overview of the current [dialects and how they interact](includes/img/dialects.svg):

<p align="center"><img src="includes/img/dialects.svg"/></p>

## Motivation

The EDA industry has well-known and widely used proprietary and open source
tools.  However, these tools are inconsistent, have usability concerns, and were
not designed together into a common platform.  Furthermore
these tools are generally built with
[Verilog](https://en.wikipedia.org/wiki/Verilog) (also
[VHDL](https://en.wikipedia.org/wiki/VHDL)) as the IRs that they
interchange.  Verilog has well known design issues, and limitations, e.g.
suffering from poor location tracking support.

The CIRCT project is an (experimental!) effort looking to apply MLIR and
the LLVM development methodology to the domain of hardware design tools.  Many
of us dream of having reusable infrastructure that is modular, uses
library-based design techniques, is more consistent, and builds on the best
practices in compiler infrastructure and compiler design techniques.

By working together, we hope that we can build a new center of gravity to draw
contributions from the small (but enthusiastic!) community of people who work
on open hardware tooling.  In turn we hope this will propel open tools forward,
enables new higher-level abstractions for hardware design, and
perhaps some pieces may even be adopted by proprietary tools in time.

For more information, please see our longer [charter document](docs/Charter.md).
