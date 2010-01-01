# Copyright (C) 2007-2009 Stefan Vigerske
# All Rights Reserved.
# This file is distributed under the Common Public License.

## $Id$

AUTOMAKE_OPTIONS = foreign

EXTRA_DIST = get.GLPK INSTALL.Glpk glpk.patch

if COIN_BUILD_GLPK
  noinst_LTLIBRARIES = libcoinglpk.la
else
  noinst_LTLIBRARIES =
endif

GLPKDIR = @GLPKDIR@

nodist_libcoinglpk_la_SOURCES = \
$(GLPKDIR)/src/glpapi01.c \
$(GLPKDIR)/src/glpapi02.c \
$(GLPKDIR)/src/glpapi03.c \
$(GLPKDIR)/src/glpapi04.c \
$(GLPKDIR)/src/glpapi05.c \
$(GLPKDIR)/src/glpapi06.c \
$(GLPKDIR)/src/glpapi07.c \
$(GLPKDIR)/src/glpapi08.c \
$(GLPKDIR)/src/glpapi09.c \
$(GLPKDIR)/src/glpapi10.c \
$(GLPKDIR)/src/glpapi11.c \
$(GLPKDIR)/src/glpapi12.c \
$(GLPKDIR)/src/glpapi13.c \
$(GLPKDIR)/src/glpapi14.c \
$(GLPKDIR)/src/glpapi15.c \
$(GLPKDIR)/src/glpapi16.c \
$(GLPKDIR)/src/glpapi17.c \
$(GLPKDIR)/src/glpapi18.c \
$(GLPKDIR)/src/glpapi19.c \
$(GLPKDIR)/src/glpapi20.c \
$(GLPKDIR)/src/glpavl.c \
$(GLPKDIR)/src/glpbfd.c \
$(GLPKDIR)/src/glpbfx.c \
$(GLPKDIR)/src/glpcpx.c \
$(GLPKDIR)/src/glpdmp.c \
$(GLPKDIR)/src/glpdmx.c \
$(GLPKDIR)/src/glpfhv.c \
$(GLPKDIR)/src/glpgmp.c \
$(GLPKDIR)/src/glphbm.c \
$(GLPKDIR)/src/glpini01.c \
$(GLPKDIR)/src/glpini02.c \
$(GLPKDIR)/src/glpios01.c \
$(GLPKDIR)/src/glpios02.c \
$(GLPKDIR)/src/glpios03.c \
$(GLPKDIR)/src/glpios04.c \
$(GLPKDIR)/src/glpios05.c \
$(GLPKDIR)/src/glpios06.c \
$(GLPKDIR)/src/glpios07.c \
$(GLPKDIR)/src/glpios08.c \
$(GLPKDIR)/src/glpios09.c \
$(GLPKDIR)/src/glpios10.c \
$(GLPKDIR)/src/glpios11.c \
$(GLPKDIR)/src/glpios12.c \
$(GLPKDIR)/src/glpipm.c \
$(GLPKDIR)/src/glpipp01.c \
$(GLPKDIR)/src/glpipp02.c \
$(GLPKDIR)/src/glplib01.c \
$(GLPKDIR)/src/glplib02.c \
$(GLPKDIR)/src/glplib03.c \
$(GLPKDIR)/src/glplib04.c \
$(GLPKDIR)/src/glplib05.c \
$(GLPKDIR)/src/glplib06.c \
$(GLPKDIR)/src/glplib07.c \
$(GLPKDIR)/src/glplib08.c \
$(GLPKDIR)/src/glplib09.c \
$(GLPKDIR)/src/glplib10.c \
$(GLPKDIR)/src/glplib11.c \
$(GLPKDIR)/src/glplib12.c \
$(GLPKDIR)/src/glplpf.c \
$(GLPKDIR)/src/glplpx01.c \
$(GLPKDIR)/src/glplpx02.c \
$(GLPKDIR)/src/glplpx03.c \
$(GLPKDIR)/src/glplpx04.c \
$(GLPKDIR)/src/glpluf.c \
$(GLPKDIR)/src/glplux.c \
$(GLPKDIR)/src/glpmat.c \
$(GLPKDIR)/src/glpmpl01.c \
$(GLPKDIR)/src/glpmpl02.c \
$(GLPKDIR)/src/glpmpl03.c \
$(GLPKDIR)/src/glpmpl04.c \
$(GLPKDIR)/src/glpmpl05.c \
$(GLPKDIR)/src/glpmpl06.c \
$(GLPKDIR)/src/glpmps.c \
$(GLPKDIR)/src/glpnet01.c \
$(GLPKDIR)/src/glpnet02.c \
$(GLPKDIR)/src/glpnet03.c \
$(GLPKDIR)/src/glpnet04.c \
$(GLPKDIR)/src/glpnet05.c \
$(GLPKDIR)/src/glpnet06.c \
$(GLPKDIR)/src/glpnet07.c \
$(GLPKDIR)/src/glpnet08.c \
$(GLPKDIR)/src/glpnpp01.c \
$(GLPKDIR)/src/glpnpp02.c \
$(GLPKDIR)/src/glpnpp03.c \
$(GLPKDIR)/src/glpnpp04.c \
$(GLPKDIR)/src/glpqmd.c \
$(GLPKDIR)/src/glprgr.c \
$(GLPKDIR)/src/glprng01.c \
$(GLPKDIR)/src/glprng02.c \
$(GLPKDIR)/src/glpscf.c \
$(GLPKDIR)/src/glpscl.c \
$(GLPKDIR)/src/glpsdf.c \
$(GLPKDIR)/src/glpspm.c \
$(GLPKDIR)/src/glpspx01.c \
$(GLPKDIR)/src/glpspx02.c \
$(GLPKDIR)/src/glpsql.c \
$(GLPKDIR)/src/glpssx01.c \
$(GLPKDIR)/src/glpssx02.c \
$(GLPKDIR)/src/amd/amd_1.c \
$(GLPKDIR)/src/amd/amd_2.c \
$(GLPKDIR)/src/amd/amd_aat.c \
$(GLPKDIR)/src/amd/amd_control.c \
$(GLPKDIR)/src/amd/amd_defaults.c \
$(GLPKDIR)/src/amd/amd_dump.c \
$(GLPKDIR)/src/amd/amd_info.c \
$(GLPKDIR)/src/amd/amd_order.c \
$(GLPKDIR)/src/amd/amd_postorder.c \
$(GLPKDIR)/src/amd/amd_post_tree.c \
$(GLPKDIR)/src/amd/amd_preprocess.c \
$(GLPKDIR)/src/amd/amd_valid.c \
$(GLPKDIR)/src/colamd/colamd.c

# CoinUtils and SYMPHONY include glpmpl.h, have HAVE_CONFIG_H defined,
# and so Glpk attempts to include config.h.
# Therefore, we put a simple config.h file into $(GLPKDIR)/include.
# It's purpose is to include the config_glpk.h file that is generated
# by configure.
libcoinglpk_la_DEPENDENCIES = $(srcdir)/$(GLPKDIR)/include/config.h \
  $(srcdir)/$(GLPKDIR)/include/glpmpl.h \
  $(srcdir)/$(GLPKDIR)/include/glpavl.h \
  $(srcdir)/$(GLPKDIR)/include/glprng.h \
  $(srcdir)/$(GLPKDIR)/include/glpdmp.h \
  $(srcdir)/$(GLPKDIR)/include/glplib.h \
  $(srcdir)/$(GLPKDIR)/include/glpstd.h

$(srcdir)/$(GLPKDIR)/include/config.h : $(srcdir)/config.h
	cp $(srcdir)/config.h $(srcdir)/$(GLPKDIR)/include/config.h

$(srcdir)/$(GLPKDIR)/include/glpmpl.h : $(srcdir)/$(GLPKDIR)/src/glpmpl.h
	cp $(srcdir)/$(GLPKDIR)/src/glpmpl.h $(srcdir)/$(GLPKDIR)/include/glpmpl.h

$(srcdir)/$(GLPKDIR)/include/glpavl.h : $(srcdir)/$(GLPKDIR)/src/glpavl.h
	cp $(srcdir)/$(GLPKDIR)/src/glpavl.h $(srcdir)/$(GLPKDIR)/include/glpavl.h

$(srcdir)/$(GLPKDIR)/include/glprng.h : $(srcdir)/$(GLPKDIR)/src/glprng.h
	cp $(srcdir)/$(GLPKDIR)/src/glprng.h $(srcdir)/$(GLPKDIR)/include/glprng.h

$(srcdir)/$(GLPKDIR)/include/glpdmp.h : $(srcdir)/$(GLPKDIR)/src/glpdmp.h
	cp $(srcdir)/$(GLPKDIR)/src/glpdmp.h $(srcdir)/$(GLPKDIR)/include/glpdmp.h

$(srcdir)/$(GLPKDIR)/include/glplib.h : $(srcdir)/$(GLPKDIR)/src/glplib.h
	cp $(srcdir)/$(GLPKDIR)/src/glplib.h $(srcdir)/$(GLPKDIR)/include/glplib.h

$(srcdir)/$(GLPKDIR)/include/glpstd.h : $(srcdir)/$(GLPKDIR)/src/glpstd.h
	cp $(srcdir)/$(GLPKDIR)/src/glpstd.h $(srcdir)/$(GLPKDIR)/include/glpstd.h

DEFAULT_INCLUDES = -I. -I`$(CYGPATH_W) $(srcdir)`

AM_CPPFLAGS = -I`$(CYGPATH_W) $(srcdir)/$(GLPKDIR)/include` \
  -I`$(CYGPATH_W) $(srcdir)/$(GLPKDIR)/src` \
  -I`$(CYGPATH_W) $(srcdir)/$(GLPKDIR)/src/amd` \
  -I`$(CYGPATH_W) $(srcdir)/$(GLPKDIR)/src/colamd` \
  -I$(GLPKDIR)

libcoinglpk_la_LDFLAGS = $(LT_LDFLAGS)

########################################################################
#                         Maintainer Stuff                             #
########################################################################

# Files that are generated and should be cleaned with make distclean
DISTCLEANFILES = $(MAKEOKFILE)

include ../../BuildTools/Makemain.inc
