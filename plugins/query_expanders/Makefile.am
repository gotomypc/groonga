EXTRA_DIST =					\
	CMakeLists.txt

INCLUDES =			\
	-I$(top_builddir)	\
	-I$(top_srcdir)/include	\
	-I$(top_srcdir)/lib

AM_LDFLAGS =					\
	-avoid-version				\
	-module					\
	-no-undefined

LIBS =						\
	$(top_builddir)/lib/libgroonga.la

query_expanders_plugins_LTLIBRARIES =
query_expanders_plugins_LTLIBRARIES += tsv.la

include tsv_sources.am
