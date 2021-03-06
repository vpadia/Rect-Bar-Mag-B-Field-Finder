# Rectangular Bar Magnet Magnetic Flux Field Finder

Function written in Java.

## Returns:
B field vector (in the form of a 3 element array, with units: Teslas) from a rectangular bar magnet at the coordinates of the point specified (coordinate origin is at the center of the magnet)

## Arguments:<br />
- x, y, z (type: double) are the coordinates of the point at which the B field is found in meters<br />
- mx, my, mz (type: double) are the width, height, and depth of the rectangular bar magnet in meters<br />
- mag_dir (type: double) is the vector of the magnetization of the magnet in A/m,<br />
  * it is confined to the y direction in A/m<br />
  * positive inputs represent a magnetization in the positive y direction<br />
    * i.e. the position of the north end of the magnet has a positive y value<br />
  * negative inputs represent a magnetization in the negative y direction<br />
    * i.e. the position of the north end of the magnet has a negative y value<br />
    
## Sources:
The equations used to calculate the magnetic field were found from journal 1 by Vlatko Cingoski and Hideo Yamashita, provided here in the Sources folder.
