#	@(#)Makefile	5.6 (Berkeley) 4/23/91

PROG=	w
NONSTDINC= ${INCOLDBSD}
SRCS=	attime.c w.c proc_compare.c
#CFLAGS+=-I/sys
MAN1=	w.0 uptime.0
DPADD=	${LIBUTIL}
LDADD=	-lutil
BINGRP=	kmem
BINMODE=2555
LINKS=	${BINDIR}/w ${BINDIR}/uptime

.include <bsd.prog.mk>
