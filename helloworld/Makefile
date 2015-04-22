TARGETS := $(notdir $(SOURCE_DIR)).bin

ENTRY_POINT := _sel4_start

CFILES   := $(patsubst $(SOURCE_DIR)/%,%,$(wildcard $(SOURCE_DIR)/src/*.c))

LIBS = c sel4 sel4muslcsys platsupport sel4platsupport

CFLAGS += -Werror -g

include $(SEL4_COMMON)/common.mk
