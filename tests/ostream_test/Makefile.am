noinst_PROGRAMS += ostream_test

ostream_test_sources = %D%/main.cxx
ostream_test_SOURCES = $(ostream_test_sources)

ostream_test_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += ostream_testU
ostream_testU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
ostream_testU_SOURCES = $(ostream_test_sources)
ostream_testU_LDADD = $(liblog4cplusU_la_file)
endif
