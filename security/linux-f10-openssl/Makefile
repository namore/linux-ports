# Created by: bsam
# $FreeBSD: head/security/linux-f10-openssl/Makefile 340722 2014-01-22 17:00:46Z mat $

PORTNAME=	openssl
PORTVERSION=	0.9.8g
PORTREVISION=	1
CATEGORIES=	security linux
MASTER_SITES=	CRITICAL/rpm/${LINUX_RPM_ARCH}/fedora/${LINUX_DIST_VER}

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	OpenSSL toolkit (Linux Fedora 10)

CONFLICTS=	linux-openssl-[0-9]* linux-f8-openssl-[0-9]*

USE_LINUX_RPM=	yes

RPMVERSION=	14.fc10
BRANDELF_FILES=	usr/bin/openssl
USE_LDCONFIG=	yes

PLIST_SUB+=	PORTVERSION="${PORTVERSION}"
DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr

.include <bsd.port.mk>
