
## Assignment I - Kaprekar Numbers

This repo contains code and tests for a simple GitHub assignment in used in Computer Science I at the University of Nebraska-Lincoln.  It contains code to compute whether or not a given integer is a Kaprekar number. It contains ad-hoc testing suites as well as examples of the cmocka formal testing framework.


### Build and Test

A `makefile` is provided that specifies how to build the various parts of the project. You can build the demo using:

`make kaprekarDemo`

and then run it from the command line using

`./kaprekarDemo 297`

An ad-hoc testing program has been provided as well which can be built using

`make kaprekarTest`

and then run it from the command line using

`./kaprekarTest`

An alternative version, `kaprekarTestCmocka.c` has been provided that uses a formal unit testing framework called cmocka (https://cmocka.org/).  It can be built using:

`make kaprekarTestCmocka`

which produces an executable, `kaprekarTestCmocka`.  This will only work if you have cmocka installed on your system.

It has thus far been fixed.

- Daniel Shchur
