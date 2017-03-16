#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([MCPE Ocelots-are-Cuter Addon],
        [0.0.1],
        [https://github.com/depressed-pho/mcpe-ocelots-are-cuter-addon/issues],
        [],
        [https://github.com/depressed-pho/mcpe-ocelots-are-cuter-addon])
AM_INIT_AUTOMAKE([1.9])
AC_CONFIG_SRCDIR([data/manifest.json.in])

AM_MAINTAINER_MODE
AM_SILENT_RULES([yes])

# Checks for programs.
AC_ARG_VAR([ZIP], [The Info-Zip zip command @<:@autodetected@:>@])
AC_CHECK_PROGS([ZIP], [zip])
AS_IF([test "x$ZIP" = x],
      [AC_MSG_ERROR([You need to install the Info-Zip zip command.])])

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([
    Makefile
    data/Makefile
    data/manifest.json
])
AC_OUTPUT
