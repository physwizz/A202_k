# SPDX-License-Identifier: GPL-2.0
dtb-y += exynos/dtbo/exynos7885.dtb
<<<<<<< HEAD
dtbo-y += exynos/dtbo/exynos7884B-a20e_eur_open_00.dtbo
dtbo-y += exynos/dtbo/exynos7884B-a20e_eur_open_03.dtbo
=======
>>>>>>> 58964d1fa... a20: dtbo: configure dtbo generation

dtb-$(CONFIG_MACH_EXYNOS7885_A20_GLOBAL) := \
	exynos/dtbo/exynos7884B-a20_cis_ser_00.dtbo \
	exynos/dtbo/exynos7884B-a20_cis_ser_01.dtbo \
	exynos/dtbo/exynos7884B-a20_cis_ser_03.dtbo \
	exynos/dtbo/exynos7884B-a20_aus_xsa_00.dtbo \
	exynos/dtbo/exynos7884B-a20_aus_xsa_01.dtbo \
	exynos/dtbo/exynos7884B-a20_aus_xsa_03.dtbo \
	exynos/dtbo/exynos7884B-a20_can_single_03.dtbo \
	exynos/dtbo/exynos7884B-a20_can_single_05.dtbo \
	exynos/dtbo/exynos7884B-a20_kor_skt_00.dtbo \
	exynos/dtbo/exynos7884B-a20_kor_skt_01.dtbo \
	exynos/dtbo/exynos7884B-a20_kor_skt_03.dtbo \
	exynos/dtbo/exynos7884B-a20_sea_xtc_00.dtbo \
	exynos/dtbo/exynos7884B-a20_sea_xtc_01.dtbo \
	exynos/dtbo/exynos7884B-a20_sea_xtc_03.dtbo \
	exynos/dtbo/exynos7884B-a20_swa_open_00.dtbo \
	exynos/dtbo/exynos7884B-a20_swa_open_01.dtbo \
	exynos/dtbo/exynos7884B-a20_swa_open_03.dtbo

ifeq ($(CONFIG_MACH_EXYNOS7885_A20_GLOBAL),y)
always         := $(dtb-y) $(dtbo-y)
clean-files    := *.dtb *.dtbo
endif

