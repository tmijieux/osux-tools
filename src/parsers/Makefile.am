include $(top_srcdir)/common.mk

bin_PROGRAMS = parse_replay parse_beatmap

parse_replay_SOURCES = parse_replay.c
parse_replay_CFLAGS = $(OSUX_CFLAGS) $(AM_CFLAGS)
parse_replay_LDFLAGS = $(OSUX_LIBS) $(AM_LDFLAGS)

parse_beatmap_SOURCES = beatmap_parser.c
parse_beatmap_CFLAGS = $(OSUX_CFLAGS) $(AM_CFLAGS)
parse_beatmap_LDFLAGS = $(OSUX_LIBS) $(AM_LDFLAGS)
