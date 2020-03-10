CONTIKI_PROJECT = node
all: $(CONTIKI_PROJECT)

CONTIKI = ../../..
-include $(CONTIKI)/Makefile.identify-target

MODULES_REL += $(TARGET)

# MAC layer configuration
MAKE_MAC = MAKE_MAC_NULLMAC

# Network layer configuration
MAKE_NET = MAKE_NET_NULLNET

include $(CONTIKI)/Makefile.include

# For automatic filename renaming
DEVICE_NAME = NODE

include ../Makefile.common
