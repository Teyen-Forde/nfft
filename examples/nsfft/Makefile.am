# $Id: Makefile.am 3654 2011-10-13 12:02:47Z rahi $

AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS = simple_test nsfft_test

simple_test_SOURCES = simple_test.c
simple_test_LDADD = $(top_builddir)/libnfft3.la @fftw3_LDFLAGS@ @fftw3_LIBS@

nsfft_test_SOURCES = nsfft_test.c
nsfft_test_LDADD = $(top_builddir)/libnfft3.la @fftw3_LDFLAGS@ @fftw3_LIBS@

EXTRA_DIST = README
