# Шлях до заголовкових файлів
AM_CPPFLAGS = -I$(top_srcdir)/src

# Виконувані файли
bin_PROGRAMS = cjpeg djpeg

# Джерела для cjpeg та djpeg
cjpeg_SOURCES = cdjpeg.c cjpeg.c
djpeg_SOURCES = cdjpeg.c djpeg.c

# Лінкування з бібліотекою
cjpeg_LDADD = $(top_builddir)/src/libmystring.la
djpeg_LDADD = $(top_builddir)/src/libmystring.la

