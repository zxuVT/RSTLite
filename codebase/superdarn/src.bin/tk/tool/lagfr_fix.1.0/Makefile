# Makefile for make_fit
# =====================
# Author: R.J.Barnes
# by R.J.Barnes
#
#
include $(MAKECFG).$(SYSTEM)

INCLUDE=-I$(IPATH)/base -I$(IPATH)/general -I$(IPATH)/superdarn
OBJS = lagfr_fix.o

SRC=lagfr_fix.c

DSTPATH = $(BINPATH)
OUTPUT = lagfr_fix
LIBS=-loldraw.1 -loldfit.1 -lcfit.1 -lrscan.1 -lradar.1 -lfitacf.1 -lraw.1 -lfit.1 -ldmap.1 -lopt.1 -lrtime.1 -lrcnv.1 -lrmath.1
SLIB=-lm -lz


include $(MAKEBIN).$(SYSTEM)
