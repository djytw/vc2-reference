AM_CXXFLAGS = \
	-I$(top_srcdir)/src/ \
	-I$(top_srcdir)/src/Library/ \
	$(VC2REFERENCE_CFLAGS) \
	$(BOOST_CFLAGS)

AM_LDFLAGS = $(VC2REFERENCE_LDFLAGS)

LDADD = ../Library/libVC2.la \
	$(BOOST_LDFLAGS) \
	$(BOOST_SYSTEM_LIB)\
	$(BOOST_THREAD_LIB)

bin_PROGRAMS = EncodeHQ-CBR

EncodeHQ_CBR_SOURCES = \
	EncodeHQ-CBR.cpp \
	EncodeParams.cpp

noinst_HEADERS = \
	EncodeParams.h
