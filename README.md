# Basic_Trajectory_Maker
Super basic trajectory plotter to get me to refamiliarize myself in Python again.

It provides the relative X, Y, and Z coordinates over a timescale of 265 seconds with time intervals of a tenth of a second for a target encircling a stationary radar across its search sector. The target maintains a fixed distance of 80000 meters away from the radar, and the search sector angle is 120 degrees. The speed of the target is 210 m/s, and the time, X, Y, and Z intervals are to be mapped in a single array. A Python script must also be able to generate a text file containing this array, delimited by a single space character. This text file must have an extension '.trj'.

Planning on making this more versatile, but for now should work as intended.
