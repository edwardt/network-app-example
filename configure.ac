AC_INIT([network-app-example], [1.0.0], [kerem@medratech.com])

AC_PREREQ([2.64])
AC_COPYRIGHT([Copyright (C) 2009 H. Kerem Cevahir])
AM_INIT_AUTOMAKE

AC_ERLANG_NEED_ERLC
AC_PREFIX_PROGRAM(erl)
AC_ERLANG_SUBST_ROOT_DIR
AC_ERLANG_SUBST_ERTS_VER
AC_ERLANG_SUBST_LIB_DIR
AC_ERLANG_CHECK_LIB([kernel])
AC_ERLANG_CHECK_LIB([stdlib])
AC_ERLANG_CHECK_LIB([edoc])
AC_ERLANG_CHECK_LIB([eunit])
AC_ERLANG_SUBST_INSTALL_LIB_SUBDIR([netapp], [1.0.0])

AC_CONFIG_FILES([Makefile src/netapp.app src/netapp.rel src/overview.edoc
	src/Makefile])
AC_OUTPUT
