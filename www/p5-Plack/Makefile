# $OpenBSD: Makefile,v 1.7 2014/12/25 15:53:29 millert Exp $

COMMENT =		interface between perl web frameworks and web servers

MODULES =		cpan
DISTNAME =		Plack-1.0033
CATEGORIES =		www
MAINTAINER =		Abel Abraham Camarillo Ojeda <acamari@verlet.org>

# Perl
PERMIT_PACKAGE_CDROM =	Yes

BUILD_DEPENDS = 	${RUN_DEPENDS}
RUN_DEPENDS =		devel/p5-Devel-StackTrace>=1.23 \
			devel/p5-Devel-StackTrace-AsHTML>=0.11 \
			devel/p5-File-pushd \
			devel/p5-File-ShareDir>=1.00 \
			devel/p5-Hash-MultiValue>=0.05 \
			devel/p5-Test-Requires \
			devel/p5-Try-Tiny \
			net/p5-Test-TCP>=2.00 \
			sysutils/p5-Filesys-Notify-Simple \
			www/fcgi \
			www/p5-libwww>=5.814 \
			www/p5-libapreq \
			www/p5-CGI-Compile \
			www/p5-FCGI-ProcManager \
			www/p5-HTTP-Body>=1.06 \
			www/p5-URI>=1.59 \
			devel/p5-Stream-Buffered \
			www/p5-Apache-LogFormat-Compiler

.include <bsd.port.mk>
