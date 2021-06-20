AM_CFLAGS = $(WFLAGS)

sbin_PROGRAMS = \
	metalog

AM_CPPFLAGS = \
	-D 'DATADIR="$(datadir)"' \
	-D 'RUNSTATEDIR="$(runstatedir)"' \
	-D 'SYSCONFDIR="$(sysconfdir)"'

metalog_SOURCES = \
	helpers.h \
	metalog.c \
	metalog.h \
	metalog_p.h
	syslognames.h

metalog_LDADD =
