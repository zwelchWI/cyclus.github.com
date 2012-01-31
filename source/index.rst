.. Cyclus documentation master file, created by
   sphinx-quickstart on Fri Jan 27 22:22:30 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Cyclus
======

As a successor to *GENIUS*, the next-generation fuel cycle systems analysis
simulation tool, *Cyclus* will preserve many of its key features with a
software architecture that provides a great deal of ﬂexibility, both in
terms of modifying the underlying modeling algorithms and presenting
different levels of complexity to different users.

The Cyclus modeling paradigm will let users reconﬁgure the basic building
blocks of a simulation without changing the software. The foundation of a
simulation will be a commodity market that collects offers and requests and
matches them according to some algorithm. The user will be able to select
which type of algorithm is used for each market by selecting a MarketModel
and conﬁguring it with a particular set of parameters defined by that
MarketModel. Changing the parameters of a market will change its
performance and selecting a different MarketModel will completely change
its behavior.

Most cyclus core code development at this time will be led by Paul Wilson,
Katy Huff, Matthew Gidden, and Robert Carlsen, the CNERG fuel cycle group.

Interested developers are welcome and encouraged to contribute but will
experience significant code instability in the early experimental stages of
the project.

Learn More
----------

.. toctree::
   :maxdepth: 2

   basics/main
   usrdoc/main
   devdoc/main

