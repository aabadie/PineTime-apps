# name of your application
APPLICATION = PineTime

BOARD ?= pinetime

# This has to be the absolute path to the RIOT base directory:
PINETIMEBASE ?= $(CURDIR)/../..

CFLAGS += -I$(CURDIR)

DEVELHELP ?= 1

USEWIDGETS += home_time
USEWIDGETS += menu_tiles
USEWIDGETS += sysinfo
USEWIDGETS += face_notification
USEWIDGETS += face_sports

# basic modules
include $(CURDIR)/modules.mk

include $(PINETIMEBASE)/Makefile.include
