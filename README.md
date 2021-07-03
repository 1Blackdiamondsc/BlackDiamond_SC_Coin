#! /bin/sh
## DO NOT EDIT - This file generated from ./build-aux/ltmain.in
##               by inline-source v2014-01-03.01

# libtool (GNU libtool) 2.4.6
# Provide generalized library-building support services.
# Written by Gordon Matzigkeit <gord@gnu.ai.mit.edu>, 1996

# Copyright (C) 1996-2015 Free Software Foundation, Inc.
# This is free software; see the source for copying conditions.  There is NO
# warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

# GNU Libtool is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# As a special exception to the GNU General Public License,
# if you distribute this file as part of a program or library that
# is built using GNU Libtool, you may include this file under the
# same distribution terms that you use for the rest of that program.
#
# GNU Libtool is distributed in the hope that it will be useful, but
# WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.


PROGRAM=libtool
PACKAGE=libtool
VERSION="2.4.6 Debian-2.4.6-2"
package_revision=2.4.6


## ------ ##
## Usage. ##
## ------ ##

# Run './libtool --help' for help with using this script from the
# command line.


## ------------------------------- ##
## User overridable command paths. ##
## ------------------------------- ##

# After configure completes, it has a better idea of some of the
# shell tools we need than the defaults used by the functions shared
# with bootstrap, so set those here where they can still be over-
# ridden by the user, but otherwise take precedence.

: ${AUTOCONF="autoconf"}
: ${AUTOMAKE="automake"}


## -------------------------- ##
## Source external libraries. ##
## -------------------------- ##

# Much of our low-level functionality needs to be sourced from external
# libraries, which are installed to $pkgauxdir.

# Set a version string for this script.
scriptversion=2015-01-20.17; # UTC

# General shell script boiler plate, and helper functions.
# Written by Gary V. Vaughan, 2004

# Copyright (C) 2004-2015 Free Software Foundation, Inc.
# This is free software; see the source for copying conditions.  There is NO
# warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3 of the License, or
# (at your option) any later version.

# As a special exception to the GNU General Public License, if you distribute
# this file as part of a program or library that is built using GNU Libtool,
# you may include this file under the same distribution terms that you use
# for the rest of that program.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNES FOR A PARTICULAR PURPOSE. See the GNU
# General Public License for more details.

# You should have received a copy of the GNU General Public License
# along with this program. If not, see <http://www.gnu.org/licenses/>.

# Please report bugs or propose patches to gary@gnu.org.


## ------ ##
## Usage. ##
## ------ ##

# Evaluate this file near the top of your script to gain access to
# the functions and variables defined here:
#
#   . `echo "$0" | ${SED-sed} 's|[^/]*$||'`/build-aux/funclib.sh
#
# If you need to override any of the default environment variable
# settings, do that before evaluating this file.


## -------------------- ##
## Shell normalisation. ##
## -------------------- ##

# Some shells need a little help to be as Bourne compatible as possible.
# Before doing anything else, make sure all that help has been provided!
