#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

# Autoconf
AC_PREREQ([2.64])
AC_INIT([ipfs-hasher], [0.0.0], [https://github.com/triton/ipfs-hasher], [ipfs-hasher], [william@wkennington.com])

AC_CONFIG_HEADERS([config])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_AUX_DIR([build-aux])

AM_INIT_AUTOMAKE([1.11 foreign dist-xz no-dist-gzip parallel-tests subdir-objects silent-rules tar-ustar])
AM_SILENT_RULES([yes])

LT_PREREQ([2.2])
LT_INIT

AC_PROG_CXX
AC_PROG_CXX_C_O
AX_CXX_COMPILE_STDCXX_11(, mandatory)
AC_LANG([C++])

AC_CONFIG_FILES([
  Makefile
  src/Makefile
  test/Makefile
])
AC_OUTPUT
