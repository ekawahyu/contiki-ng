CONTIKI_PROJECT = button-hal-example
CONTIKI = ../../..
MODULES += os/services/simple-energest
MODULES += os/services/shell

all: $(CONTIKI_PROJECT)

PLATFORMS_ONLY += cc26x0-cc13x0 cc2538dk openmote zoul simplelink
PLATFORMS_ONLY += cooja native

MAKE_MAC ?= MAKE_MAC_CSMA
MAKE_NET = MAKE_NET_NULLNET
include $(CONTIKI)/Makefile.include
