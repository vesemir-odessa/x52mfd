
ACLOCAL_AMFLAGS	=	-I m4

bin_PROGRAMS	=	x52mfd


x52mfd_SOURCES	=	src/main.c		\
					src/reader.c	\
					src/writer.c	\
					src/sopen.c		\
					src/connector.c	\
					src/plog.c		\
					include/x52mfd.h

x52mfd_CFLAGS	=	-I$(top_srcdir)/include $(X52LIB_CFLAGS) $(LIBX52IO_CFLAGS)
x52mfd_LDFLAGS	=	
x52mfd_LDADD	=	$(LIBX52_LIBS) $(LIBX52IO_LIBS)

SUBDIRS			=	$(subdirs)
DIST_SUBDIRS	=	$(SUBDIRS)


