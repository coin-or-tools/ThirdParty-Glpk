# Copyright (C) 2007-2010 Stefan Vigerske and others.
# All Rights Reserved.
# This file is distributed under the Eclipse Public License.

## $Id$

#############################################################################
#                       Names and other basic things                        #
#############################################################################

AC_INIT([ThirdPartyGlpk],[trunk],
  [http://projects.coin-or.org/BuildTools/newticket],[thirdpartyglpk],
  [http://projects.coin-or.org/BuildTools/browser/ThirdParty/Glpk])

AC_COPYRIGHT([
Copyright 2007-2010 Stefan Vigerske and others.
All Rights Reserved.
This file is part of the open source package ThirdParty/Glpk which is
distributed under the Eclipse Public License.])

# List one file in the package so that the configure script can test whether
# the package is actually there.

AC_CONFIG_SRCDIR(glpk/src/glpk.h)

# Do some generic initialization work.

AC_COIN_INITIALIZE(Glpk)

#############################################################################
#                         Standard build tool stuff                         #
#############################################################################

# Get the name of the C compiler and appropriate compiler options.

AC_COIN_PROG_CC

# Set up libtool.

AC_COIN_PROG_LIBTOOL

# Make it appear as if --includedir was part of the command line, so that
# glpk's install will put glpk.h in the proper place. Suppress reentrancy &
# static library generation. Pass CFLAGS via a cache variable to avoid
# complaints about changing the environment.

ac_configure_args="$ac_configure_args --includedir=\\\${prefix}/include/coin-or/ThirdParty"
ac_configure_args="$ac_configure_args --enable-reentrant=no"
ac_configure_args="$ac_configure_args --enable-static=no"

ctpglpk_cv_cflags="$CFLAGS"

# Invoke glpk's native configuration

AC_CONFIG_SUBDIRS(glpk)

# Finish up

AC_CONFIG_FILES([Makefile coinglpk.pc])
AC_CONFIG_HEADER([config_glpk.h])

AC_COIN_FINALIZE

