# Created by: Artyom Mirgorodskiy <artyom.mirgorodsky@gmail.com>
# $FreeBSD$

PORTNAME=	nss
PORTVERSION=	3.15.1
CATEGORIES=	security linux

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	Network Security Services (Linux CentOS ${LINUX_DIST_VER})

DISTFILES=	${PORTNAME}-${PORTVERSION}-${RPMVERSION}.${LINUX_RPM_ARCH}.rpm \
		nss-util-3.15.1-3.el6.${LINUX_RPM_ARCH}.rpm \
		nss-softokn-3.14.3-9.el6.${LINUX_RPM_ARCH}.rpm \
		nss-softokn-freebl-3.14.3-9.el6.${LINUX_RPM_ARCH}.rpm

CONFLICTS=	linux-f10-nss-[0-9]*

ONLY_FOR_ARCHS=	i386 amd64
RPMVERSION=	15.el6
USE_LINUX=	yes
USE_LINUX_APPS=	nspr sqlite3

USE_LINUX_RPM=	yes
USE_LDCONFIG=	yes

DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
