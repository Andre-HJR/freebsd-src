.include <bsd.compiler.mk>

PROG=	wlanstats
MAN=

CFLAGS=	-I${SRCTOP}/lib/libbsdstat
LIBADD=	bsdstat

SRCS=	main.c \
	wlanstats.c

CFLAGS.clang+= -fbracket-depth=512

.include <bsd.prog.mk>
