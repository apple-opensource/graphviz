## Process this file with automake to produce Makefile.in

AUTOMAKE_OPTIONS = 1.4

INCLUDES =

LIBS =

noinst_HEADERS = tclhandle.h
if WITH_TCL
noinst_LTLIBRARIES = libtclhandle.la
endif

libtclhandle_la_SOURCES = tclhandle.c

EXTRA_DIST = $(libtclhandle_la_SOURCES) Makefile.old
