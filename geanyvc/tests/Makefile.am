if UNITTESTS
if ENABLE_GEANYVC
include $(top_srcdir)/build/vars.build.mk
INCLUDES = $(GEANY_CFLAGS) -DUNITTESTS
TESTS=unittests
noinst_PROGRAMS=unittests
unittests_SOURCES = unittests.c ../src/utils.c
unittests_LDADD  = @GEANY_LIBS@ $(INTLLIBS) @CHECK_LIBS@
endif
endif
