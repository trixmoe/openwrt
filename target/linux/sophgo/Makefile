# SPDX-License-Identifier: GPL-2.0-only
#
# Copyright (C) 2025
#
include $(TOPDIR)/rules.mk

ARCH:=riscv64
BOARD:=milkv-duo-s
BOARDNAME:=MILKV Duo-S
FEATURES:=ext4 squashfs
KERNELNAME:=Image dtbs
SUBTARGETS:=generic

KERNEL_PATCHVER:=6.12

include $(INCLUDE_DIR)/target.mk

define Target/Description
	Build firmware images for MILKV Duo-S
endef

$(eval $(call BuildTarget))
