# SPDX-License-Identifier: GPL-2.0
ifeq ($(CONFIG_ARCH_ROCKCHIP), y)

dtbo-$(CONFIG_CPU_RK3568) += \
	rk356x-darkos-uart3-m0-overlay.dtbo \
	rk356x-darkos-uart3-m0-overlay.dtbo \
	rk356x-darkos-uart3-m1-overlay.dtbo \
	rk356x-darkos-uart4-m1-overlay.dtbo \
	rk356x-darkos-uart5-m1-overlay.dtbo \
	rk356x-darkos-uart7-m1-overlay.dtbo \
	rk356x-darkos-uart8-m0-overlay.dtbo \
	rk356x-darkos-uart8-m1-overlay.dtbo \
	rk356x-darkos-uart9-m1-overlay.dtbo 
endif

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays.md

targets += $(dtbo-y) $(dtbotxt-y)

always-y		:= $(dtbo-y) $(dtbotxt-y)
clean-files		:= *.dtbo
