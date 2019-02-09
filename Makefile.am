AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = bbexampleapp.h

lib_LTLIBRARIES = libbbexampleapp.la
libbbexampleapp_la_SOURCES  = bbexampleapplib.c
libbbexampleapp_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = bbexampleapp
bbexampleapp_SOURCES = bbexampleapp.c
bbexampleapp_LDADD = libbbexampleapp.la

