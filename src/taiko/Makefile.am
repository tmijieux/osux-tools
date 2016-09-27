include $(top_srcdir)/common.mk

bin_PROGRAMS = taiko_generator taiko_converter

taiko_generator_SOURCES = generator.c generator_cmdline.c generator_cmdline.h generator.ggo
taiko_generator_CFLAGS = $(AM_CFLAGS) $(OSUX_CFLAGS)
taiko_generator_LDFLAGS = $(AM_LDFLAGS) $(OSUX_LIBS)

taiko_converter_SOURCES = converter.c
taiko_converter_CFLAGS = $(AM_CFLAGS) $(OSUX_CFLAGS)
taiko_converter_LDFLAGS = $(AM_LDFLAGS) $(OSUX_LIBS)

