## Process this file with automake to produce Makefile.in ##

AM_CPPFLAGS = -I$(srcdir)/../src

# Change name from libglpk to libcoinglpk.

LDADD = ../src/libcoinglpk.la

bin_PROGRAMS = glpsol

glpsol_SOURCES = glpsol.c

check: glpsol$(EXEEXT)
	./glpsol$(EXEEXT) --version
	./glpsol$(EXEEXT) --mps $(srcdir)/murtagh.mps --max

## eof ##
