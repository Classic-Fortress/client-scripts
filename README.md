client-scripts
==============

There are two configs included in this repository.

The first one is cfortress.cfg, which is meant to be installed in a pre-
existing QuakeWorld installation. Simply put it in your /fortress/ directory
and issue /exec cfortress.cfg in your favourite client.

You need to modify the following line in cfortress.cfg to get proper fov
and sensitivity:

alias f_spawn "set_sbar; setinfo df 90; setinfo ds 3"

Just change "90" and "3" to your prefered default fov setting and the sensitivity
that you use.


The other config file included is the default.cfg config file. It is used by
Classic Fortress to initialize default settings. It is installed in the
/fortress/ subdirectory of your Classic Fortress installation. It requires
the Classic Fortress client to function.