# GNU Gama

Gama is a Free Software package for geodesy and surveying, available
under the under the GNU General Public License, version 3 or later.
The Gama project was started in 1998, and in 2001 it became a GNU
package.

## Description

GNU Gama is a project dedicated to adjustment of surveying and
geodetic networks.  It is intended for use with traditional surveying
instruments, which are still in widespread use despite the advent of
Global Navigation Satellite Systems.  Traditional instruments are
necessary for mm-level precision in local areas, and for underground
or interior measurements.  Gama also has some support for adjustment
of networks containing GNSS observations.

Adjustment in local Cartesian coordinate systems is fully supported by
a command-line program gama-local that adjusts geodetic (free)
networks of observed distances, directions, angles, height
differences, 3D vectors and observed coordinates (coordinates with
given variance-covariance matrix). Adjustment in global coordinate
systems is supported only partly as a gama-g3 program.

## Documentation

As a GNU program, documentation is available in Texinfo format,
resulting in a pdf manual and info pages.

## Building gama

Note that the version number of the package is defined in
configure.ac (and other places as noted there).

### Prerequisites

Gama assumes a system complying with POSIX.
In addition, it requires the following programs to build a release.
  - a compiler that supports C++14
  - GNU make

To build from the repository, the following are additionally needed:
  - autoconf
  - automake
  - GNU Texinfo (7 is known to work)

### Build and Test

Beyond that, the standard autotools instructions, available in
INSTALL, apply.  Note that Gama's tests may be run via "make test".

## More information

More information on GNU Gama can be found at

                 http://www.gnu.org/software/gama

This includes links to the project page on savannah, where one can
find mailinglists, a bug tracker, and source code repository.  GNU
Gama does not have any repository mirrors.

See also MAINTAINING.md file.
