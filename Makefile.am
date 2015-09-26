SUBDIRS = . tests

# If compiling with gettext, add po subdirectory
# SUBDIRS = $SUBDIRS po

lib_LTLIBRARIES = %D%/librtmidi.la
%C%_librtmidi_la_LDFLAGS = -no-undefined
%C%_librtmidi_la_SOURCES = \
  %D%/RtMidi.cpp \
  %D%/RtMidi.h

EXTRA_DIST = config/config.rpath m4/ChangeLog
