# $FreeBSD$

PORTNAME=	roadie-rails
PORTVERSION=	1.3.0
PORTREVISION=	1
CATEGORIES=	mail rubygems
MASTER_SITES=	RG
PKGNAMESUFFIX=	52

MAINTAINER=	mikael@FreeBSD.org
COMMENT=	Helper for generating HTML mails in Rails applications

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE.txt

RUN_DEPENDS=	rubygem-railties52>=3.0:www/rubygem-railties52 \
		rubygem-roadie3>=3.1:mail/rubygem-roadie3

USES=		gem shebangfix
USE_RUBY=	yes

NO_ARCH=	yes

SHEBANG_FILES=	setup.sh

.include <bsd.port.mk>
