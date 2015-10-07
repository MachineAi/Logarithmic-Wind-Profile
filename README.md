# Logarithmic-Wind-Profile
A LabView VI to graphically illustrate the logarithmic wind profile equation for teaching purposes.

## Description

The VI "log_profile.vi" is a visualization of the logarithmic wind profile under neutral conditions. The instructor (or student) can change the friction velocity (u*) and the roughness length (z0) and the two graphs, showing wind vs. height change interactively. One graph displays the law in a linear (u) - linear (z) mapping, one graph shows linear (u) - logarithmic (z).

The VI "log_law.vi" is a helper VI that calculates for a given u*, a given z_0 and a given z the wind speed u.

A web implementation of this applet for teaching can be found here:
http://ibis.geog.ubc.ca/courses/geob300/applets/neutralwind/

## Source / License

This code has been written by Andreas Christen, Associate Professor, the University of British Columbia, Vancouver, Canada and is published for free use and modification under the GNU GPL V 2.0.
