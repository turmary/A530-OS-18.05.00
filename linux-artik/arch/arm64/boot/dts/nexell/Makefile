dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik710-raptor-rev00.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik710-raptor-rev01.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik710-raptor-rev03.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik711s-raptor-rev01.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik711s-explorer.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-artik710-explorer.dtb
dtb-$(CONFIG_ARCH_S5P6818) += s5p6818-drone.dtb

ifeq ($(CONFIG_ARCH_S5P6818),y)
	DTC_FLAGS	?= -@ -H epapr
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
