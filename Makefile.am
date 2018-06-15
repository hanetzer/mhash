#AUTOMAKE_OPTIONS = foreign
ACLOCAL_AMFLAGS = -I m4
SUBDIRS = include lib doc src
EXTRA_DIST = mhash.pc.in mhash.pc mhash.spec.in mhash.spec
pkgconfig_DATA = mhash.pc
USE_MHASH_CONFIG = yes

ChangeLog:
	cvs2cl --utc --fsf -t -S --prune
