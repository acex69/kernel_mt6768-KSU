#
# Copyright (C) 2017 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

ifeq ($(CONFIG_BUILD_ARM64_APPENDED_DTB_IMAGE_NAMES),"mediatek/mt6885_3gear")
ccflags-y += -DTRIGEAR_LEAKAGE
endif

ccflags-y += \
	-I$(srctree)/drivers/misc/mediatek/base/power/include/ \
	-I$(srctree)/drivers/misc/mediatek/base/power/include/leakage_table_v2/ \

# MT6759
obj-$(CONFIG_MACH_MT6759) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6759) += mtk_static_power_mt6759.o

# MT6763
obj-$(CONFIG_MACH_MT6763) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6763) += mtk_static_power_mt6763.o

# MT6758
obj-$(CONFIG_MACH_MT6758) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6758) += mtk_static_power_mt6758.o

# MT6739
obj-$(CONFIG_MACH_MT6739) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6739) += mtk_static_power_mt6739.o

# MT6765
obj-$(CONFIG_MACH_MT6765) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6765) += mtk_static_power_mt6765.o

# MT6771
obj-$(CONFIG_MACH_MT6771) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6771) += mtk_static_power_mt6771.o

# MT6775
obj-$(CONFIG_MACH_MT6775) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6775) += mtk_static_power_mt6775.o

# MT6768
obj-$(CONFIG_MACH_MT6768) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6768) += mtk_static_power_mt6768.o

# MT6785
obj-$(CONFIG_MACH_MT6785) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6785) += mtk_static_power_mt6785.o

# MT6885
ifeq ($(CONFIG_MACH_MT6885), y)
obj-$(CONFIG_MACH_MT6885) += mtk_static_power.o
ifeq ($(CONFIG_BUILD_ARM64_APPENDED_DTB_IMAGE_NAMES),"mediatek/mt6885")
obj-y += mtk_static_power_mt6885.o
else
obj-y += mtk_static_power_mt6893.o
endif
endif

# MT6893
obj-$(CONFIG_MACH_MT6893) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6893) += mtk_static_power_mt6893.o

# MT6873
obj-$(CONFIG_MACH_MT6873) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6873) += mtk_static_power_mt6873.o

# MT6853
obj-$(CONFIG_MACH_MT6853) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6853) += mtk_static_power_mt6853.o

# MT6833
obj-$(CONFIG_MACH_MT6833) += mtk_static_power.o

obj-$(CONFIG_MACH_MT6833) += mtk_static_power_mt6833.o

# MT8168
obj-$(CONFIG_MACH_MT8168) += mtk_static_power.o

obj-$(CONFIG_MACH_MT8168) += mtk_static_power_mt8168.o

ccflags-y += -Wno-uninitialized
