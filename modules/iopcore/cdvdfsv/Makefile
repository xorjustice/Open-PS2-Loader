IOP_BIN = cdvdfsv.irx
IOP_OBJS = cdvdfsv.o searchfile.o ncmd.o scmd.o imports.o exports.o

IOP_INCS += -I../common

ifeq ($(DEBUG),1)
IOP_CFLAGS += -DDEBUG
endif

ifeq ($(IOPCORE_DEBUG),1)
IOP_CFLAGS += -D__IOPCORE_DEBUG
endif

include $(PS2SDK)/Defs.make
include ../../Rules.bin.make
include $(PS2SDK)/samples/Makefile.iopglobal
