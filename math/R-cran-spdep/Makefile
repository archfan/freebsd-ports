# Created by: TAKATSU Tomonari <tota@FreeBSD.org>
# $FreeBSD$

PORTNAME=	spdep
DISTVERSION=	0.7-9
CATEGORIES=	math
DISTNAME=	${PORTNAME}_${DISTVERSION}

MAINTAINER=	tota@FreeBSD.org
COMMENT=	Spatial dependence: weighting schemes, statistics, and models

LICENSE=	GPLv2+

CRAN_DEPENDS=	R-cran-sp>=1.0:math/R-cran-sp \
		R-cran-spData>=0.2.6.0:math/R-cran-spData \
		R-cran-LearnBayes>0:math/R-cran-LearnBayes \
		R-cran-deldir>0:math/R-cran-deldir \
		R-cran-coda>0:math/R-cran-coda \
		R-cran-gmodels>0:devel/R-cran-gmodels \
		R-cran-expm>0:math/R-cran-expm
LIB_DEPENDS=	libopenblasp.so:math/openblas
BUILD_DEPENDS=	${CRAN_DEPENDS}
RUN_DEPENDS=	${CRAN_DEPENDS}

USES=	cran:auto-plist,compiles

.include <bsd.port.mk>
