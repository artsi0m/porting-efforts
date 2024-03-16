COMMENT=	"Tool for generating Clang's JSON Compilation Database"

MODPY_EGG_VERSION=	0.10.1
DISTNAME=	compiledb-${MODPY_EGG_VERSION}
PKGNAME= 	py-${DISTNAME}
CATEGORIES=	devel textproc sysutils

HOMEPAGE=	https://github.com/nickdiego/compiledb
#GPLv3+
PERMIT_PACKAGE=	Yes

MODPY_PI= 	Yes
MODPY_PYBUILD=	setuptools
RUN_DEPENDS=	textproc/py-bashlex \
		devel/py-click

MODULES= lang/python

FLAVOR= 	python3
FLAVORS=	python3

.include <bsd.port.mk>
