## Process this file with automake to produce Makefile.in

INCLUDES = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	@PACKAGE_CFLAGS@

bin_PROGRAMS = project-gtk

project_gtk_SOURCES = \
	main.c \
	support.c support.h \
	interface.c interface.h \
	callbacks.c callbacks.h \
	users.c	users.h	\
	event.c	event.h \
	profile.c profile.h	\
	pay.c	pay.h	\
	fichemed.c fichemed.h \
	emploimed.c	emploimed.h \
	kine.c	kine.h \
	coach.c	coach.h	\
	treeview.c treeview.h \
	reserver.c reserver.h

project_gtk_LDADD = @PACKAGE_LIBS@ $(INTLLIBS)
