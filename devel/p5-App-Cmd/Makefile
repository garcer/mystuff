# $OpenBSD $

COMMENT =		write command line apps with less suffering

MODULES =		cpan
DISTNAME =		App-Cmd-0.326
CATEGORIES =		devel

MAINTAINER =		Cesare Gargano <gar@plusiagamma.org>

BUILD_DEPENDS =		${RUN_DEPENDS}
RUN_DEPENDS =		sysutils/p5-Capture-Tiny>=0.13 \
			devel/p5-Class-Load \
			devel/p5-Data-OptList \
			devel/p5-Getopt-Long-Descriptive>=0.084 \
			devel/p5-IO-TieCombine \
			devel/p5-Module-Pluggable \
			textproc/p5-String-RewritePrefix \
			devel/p5-Sub-Exporter \
			devel/p5-Sub-Install

TEST_DEPENDS =		devel/p5-Test-Fatal

# Perl
PERMIT_PACKAGE_CDROM =	Yes

.include <bsd.port.mk>
