
AC_PREREQ(2.53)

AC_INIT([ubuntustudio-legacy-icon-theme], [1.1.4], [https://github.com/lukefromdc])

AM_INIT_AUTOMAKE([1.11 no-dist-gzip dist-xz tar-ustar check-news])

# Enable silent build rules by default, requires at least
# Automake-1.11. Disable by either passing --disable-silent-rules to
# configure or passing V=1 to make
m4_ifdef([AM_SILENT_RULES], [AM_SILENT_RULES([yes])])

PKG_PROG_PKG_CONFIG([0.19])

# Workaround to make aclocal get the right flags
AC_SUBST(ACLOCAL_AMFLAGS, "\${ACLOCAL_FLAGS}")

AC_CONFIG_FILES([
makefile
UbuntuStudio_Legacy/makefile
])

AC_OUTPUT

dnl ==========================================================================
echo "
	gtk-theme-ubuntustudio-legacy-$VERSION:

	Installation prefix:                    ${prefix}

	configuration successfully, now type make
"
