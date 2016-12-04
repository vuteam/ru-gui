installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = WirelessLan VideoClippingSetup \
	SatelliteEquipmentControl DiseqcTester HdmiCEC LCNScanner

if HAVE_LIBVUGLES2
SUBDIRS += AnimationSetup
endif

if HAVE_OSDANIMATION
SUBDIRS += AnimationSetup
endif

if DREAMBOX
SUBDIRS += FrontprocessorUpgrade NFIFlash
endif

install_PYTHON = __init__.py
