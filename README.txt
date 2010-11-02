# $Id$

The uc_iats module integrates the IATS payment gateway (http://iats.ticketmaster.com) with Ubercart.

## INSTALL ##
Just place this module in your modules directory and turn it on.


## REQUIREMENTS ##
This module, obviously, requires Ubercart.

Also, this module requires the IATSLink PHP library. As far as I'm aware, this is not available publically; you must get it directly from IATS by contacting them.

The module looks for the library in its directory, but default as a directory named 'iatslink'. So if you would like to set up with the least possible hassle, rename the library's directory to 'iatslink' and place it the 'uc_iats' module directory. This should work with no extra configuration. If you would like to name the folder something else, you can set the path to the library on the uc_iats settings page (the same place where you set the IATSLink agent code and password).