ifeq ($(CONFIG_BOARD_ALIOTH), y)
ccflags-y += -Ofast
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee.o
else ifeq ($(CONFIG_BOARD_APOLLO), y)
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee_apollo.o
endif
