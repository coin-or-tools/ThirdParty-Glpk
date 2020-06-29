# Copyright (C) 2007-2020 COIN-OR
# All Rights Reserved.
# This file is distributed under the Eclipse Public License.


#############################################################################
#                       Names and other basic things                        #
#############################################################################

AC_INIT([ThirdPartyGlpk],[trunk],
  [https://github.com/coin-or-tools/ThirdParty-Glpk/issues/new],[thirdpartyglpk],
  [https://github.com/coin-or-tools/ThirdParty-Glpk/])

AC_COPYRIGHT([
Copyright 2007-2020 COIN-OR
All Rights Reserved.
This file is part of the open source package ThirdParty-Glpk which is
distributed under the Eclipse Public License.])

# List one file in the package so that the configure script can test whether
# the package is actually there.
AC_CONFIG_SRCDIR(glpk/src/glpk.h)

# Do some generic initialization work.
AC_COIN_INITIALIZE

#############################################################################
#                         Standard build tool stuff                         #
#############################################################################

# Make it appear as if --includedir was part of the command line, so that
# glpk's install will put glpk.h in the proper place. Suppress reentrancy.

ac_configure_args="$ac_configure_args --includedir=\\\${prefix}/include/coin-or/glpk"
ac_configure_args="$ac_configure_args --enable-reentrant=no"

# Invoke glpk's native configuration
AC_CONFIG_SUBDIRS(glpk)

# Finish up
AC_CONFIG_FILES([Makefile coinglpk.pc])

AC_COIN_FINALIZE
