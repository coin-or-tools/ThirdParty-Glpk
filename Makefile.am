# Copyright (C) 2007-2009 Stefan Vigerske
# All Rights Reserved.
# This file is distributed under the Eclipse Public License.

## $Id$

AUTOMAKE_OPTIONS = foreign

EXTRA_DIST = get.GLPK INSTALL.Glpk glpk.patch

pkgconfiglibdir = $(libdir)/pkgconfig
pkgconfiglib_DATA = coinglpk.pc

# Setting SUBDIRS triggers automake to create the necessary recursion rules.

SUBDIRS=@subdirs@

unitTest test:
	@echo "Running glpk 'make check'"
	@cd glpk ; $(MAKE) check

########################################################################
#                         Maintainer Stuff                             #
########################################################################

CLEANFILES =

DISTCLEANFILES =
