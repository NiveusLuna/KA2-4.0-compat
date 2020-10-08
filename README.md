# KA2-4.0
 Klingon Academy II - move to 4.0 launcher

The goal of this project is to port Klingon Academy II to the FO 4.0 launcher.

Why, you ask? Well, the biggest reason is: decommissioning things. The 3.x
launcher always assumes that decom values are zero unless they're defined in
the ODF. Faction and shipyard decom fraction commands are ignored.

This wouldn't be much of an issue, except the ISC have a station that returns
the full value of the ship to be decommissioned. Using the ODF recycleResource
commands prevents different shipyards from granting different amounts of
resources upon decommissioning a ship. Not using those commands results in not
getting any resources at all.

It's also much less work to port the mod to 4.0 than it is to add decom values
to every ship and station in the game.

In addition, this will allow either/or tech requirements, simplifying things
like Romulan frenemy mixed tech.

Find a problem or bug introduced by the 4.0 conversion? Please verify that it
does not exist under the 3.2.7 launcher, then report it using the issue tracker.

Please note that bugs in KA2 are fixed in a different mod (linked below). The
goal of this mod is solely to make stock KA2 work as if designed for the 4.0
launcher. In developer terms, this mod is a compatibility layer between KA2 and
the FleetOps 4.0 beta launcher.
