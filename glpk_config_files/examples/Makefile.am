## Process this file with automake to produce Makefile.in ##

AM_CPPFLAGS = -I$(srcdir)/../src

AUTOMAKE_OPTIONS = gnu

# Change name from libglpk to libcoinglpk.

LDADD = ../src/libcoinglpk.la

AM_LDFLAGS = $(LT_LDFLAGS)

bin_PROGRAMS = glpsol

glpsol_SOURCES = glpsol.c

check: glpsol$(EXEEXT)
	./glpsol$(EXEEXT) --version
	./glpsol$(EXEEXT) --mps $(srcdir)/murtagh.mps --max

## eof ##
