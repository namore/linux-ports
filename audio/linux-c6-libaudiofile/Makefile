# Created by: Johannes Meixner <xmj@chaot.net>
# $FreeBSD$

PORTNAME=	libaudiofile
PORTVERSION=	0.2.6
CATEGORIES=	audio linux
DISTNAME=	audiofile-${PORTVERSION}-${RPMVERSION}

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	Implementation of the Audio File Library from SGI (Linux CentOS ${LINUX_DIST_VER})

CONTFLICTS=	linux-libaudiofile-[0-9]* linux-f10-libaudiofile-[0-9]*

USE_LINUX=	yes
USE_LINUX_RPM=	yes

RPMVERSION=	11.1.el6
BRANDELF_DIRS=	usr/bin
USE_LDCONFIG=	yes

DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
