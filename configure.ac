AC_INIT([osux], [0.1], [lmaugere@ipb.fr, tmijieux@ipb.fr])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AM_SILENT_RULES([yes])

### TOOLS ##

AC_PROG_CC
AM_PROG_AR
PKG_PROG_PKG_CONFIG
AM_GNU_GETTEXT([external])
AM_GNU_GETTEXT_VERSION([0.19.8])
LT_INIT([win32-dll disable-static])

### LIBRARIES ##

PKG_CHECK_MODULES([GLIB], [glib-2.0])
PKG_CHECK_MODULES([GMODULE], [gmodule-2.0])
PKG_CHECK_MODULES([GIO], [gio-2.0])
PKG_CHECK_MODULES([GOBJECT], [gobject-2.0])
PKG_CHECK_MODULES([OSUX], [osux-0.1])

### VARIABLES ##

### OUTPUT ##
AC_CONFIG_FILES([
                  po/Makefile.in
                  Makefile
                  src/Makefile
                  src/taiko/Makefile
                  src/parsers/Makefile
                  src/dbctl/Makefile
               ])
AC_OUTPUT
