# Created by: Artyom Mirgorodskiy <artyom.mirgorodsky@gmail.com>
# $FreeBSD$

PORTNAME=	openssl
PORTVERSION=	1.0.1e
CATEGORIES=	security linux

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	OpenSSL toolkit (Linux CentOS ${LINUX_DIST_VER})

CONFLICTS=	linux-openssl-[0-9]* linux-f8-openssl-[0-9]* linux-f10-openssl-[0-9]*

ONLY_FOR_ARCHS=	i386 amd64
USE_LINUX=	yes
USE_LINUX_RPM=	yes
RPMVERSION=	15.el6
BRANDELF_FILES=	usr/bin/openssl
USE_LDCONFIG=	yes

PLIST_SUB+=	PORTVERSION="${PORTVERSION}"
DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
